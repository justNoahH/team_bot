
const Discord = require('discord.js');

const bot = new Discord.Client();

bot.on("ready", function () {
  console.log("up");
});

const Tier = ["Tier S", "Tier A", "Tier B", "Tier C", "Tier D"];
var randomTier = Tier[Math.floor(Math.random() * Tier.length)];

bot.on("message", message => {

  if (message.content === "!rosterdev") {
      
      message.channel.send({
      embed: {
        color: 3447003,
        description: "__**Roster "Name" :trophy:**__",
        fields: [
          {
            name: "Leads",
            value: ":star: - 𝐏𝐬𝐞𝐮𝐝𝐨\n:star: - 𝐏𝐬𝐞𝐮𝐝𝐨\n..."
          }
        ]
      }
      });
  }

  if (message.content === "?help") {
      
    message.channel.send({
    embed: {
      color: 3447003,
      description: "__**Les différentes commandes**__",
      fields: [
        {
          name: "!roster",
          value: "Pour accéder au roster de la team."
        },
        {
          name: "!résultats",
          value: "Pour accéder aux résultats de la team."
        }
      ]
    }
    });
  }

  if (message.content.startsWith("!pin")) {
    message.pin();
    
}

  if (message.content === "!youtube") {
      
    message.channel.send({
    embed: {
      color: 3447003,
      description: "__**:projector: Nos chaines**__",
      fields: [
        {
          name: ":star: Pseudo",
          value: "url"
        },
        {
          name: ":star: Pseudo",
          value: "url"
        }
      ]
    }
    });
  }

  if (message.content === "!tierpseudo") {
    var randomTier = Tier[Math.floor(Math.random() * Tier.length)]
 message.channel.send(randomTier);
 }

  if (message.content === "!everyone") {
    message.channel.send("||@everyone||");
 }

  if (message.content === "!roster") {
    message.channel.send("#🔱-𝐑𝐨𝐬𝐭𝐞𝐫");
 }

  if (message.content === "!résultats") {
    message.channel.send("#🏆-𝐑𝐞́𝐬𝐮𝐥𝐭𝐚𝐭𝐬");
 }
});


bot.login("token")
