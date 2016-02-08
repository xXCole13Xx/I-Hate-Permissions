groups:
  Member:
    options:
      rank: '1000'
      default: true
      prefix: '&8[&rMember&8]&7 '
    permissions:
    - bukkit.broadcast.user
    - -bukkit.command.plugins
    - essentials.help
    - essentials.helpop
    - essentials.list
    - essentials.motd
    - essentials.rules
    - essentials.spawn
    - essentials.jail.allow.help
    - essentials.jail.allow.helpop
    - essentials.jail.allow.rules
    - essentials.afk
    - essentials.afk.auto
    - essentials.back
    - essentials.back.ondeath
    - essentials.balance
    - -essentials.balance.others
    - essentials.balancetop
    - essentials.book
    - -essentials.chat.color
    - -essentials.chat.format
    - essentials.chat.shout
    - essentials.chat.question
    - essentials.compass
    - essentials.delhome
    - essentials.depth
    - essentials.exp
    - essentials.getpos
    - essentials.home
    - essentials.ignore
    - essentials.itemdb
    - essentials.kit
    - essentials.kits.tools
    - essentials.mail
    - essentials.mail.send
    - essentials.me
    - essentials.msg
    - -essentials.msg.color
    - -essentials.msg.format
    - -essentials.nick
    - essentials.pay
    - essentials.ping
    - -essentials.powertool
    - -essentials.powertooltoggle
    - essentials.protect
    - essentials.recipe
    - essentials.seen
    - essentials.sethome
    - essentials.sethome.bed
    - -essentials.sethome.multiple
    - essentials.signs.use.*
    - essentials.signs.create.disposal
    - essentials.signs.create.mail
    - essentials.signs.create.protection
    - essentials.signs.create.trade
    - essentials.signs.break.disposal
    - essentials.signs.break.mail
    - essentials.signs.break.protection
    - essentials.signs.break.trade
    - essentials.suicide
    - essentials.time
    - essentials.tpa
    - essentials.tpaccept
    - essentials.tpahere
    - essentials.tpdeny
    - essentials.warp
    - essentials.warp.list
    - essentials.worth
    - essentials.jail.allow.mail
    - essentials.jail.allow.ping
    - essentials.jail.allow.seen
    options:
      rank: '900'
      prefix: '&8[&aMemberr&8]&7 '
  Mod:
    inheritance:
    - Member
    permissions:
    - bukkit.command.ban
    - bukkit.command.ban.ip
    - bukkit.command.ban.player
    - -bukkit.command.gamemode
    - bukkit.command.kick
    - bukkit.command.unban
    - bukkit.command.unban.ip
    - bukkit.command.unban.player
    - -essentials.spawner.enderdragon
    - essentials.afk.kickexempt
    - essentials.ban
    - essentials.ban.notify
    - essentials.banip
    - essentials.book.title
    - essentials.book.others
    - essentials.broadcast
    - essentials.chat.url
    - essentials.chat.magic
    - essentials.clearinventory
    - -essentials.delwarp
    - -essentials.eco.loan
    - -essentials.exp.others
    - essentials.ext
    - essentials.getpos
    - essentials.getpos.others
    - essentials.helpop.receive
    - essentials.home.others
    - essentials.invsee
    - essentials.jails
    - -essentials.jump
    - essentials.kick
    - essentials.kick.notify
    - -essentials.kill
    - essentials.kits.*
    - essentials.msg.magic
    - essentials.mute
    - essentials.mute.notify
    - -essentials.nick.color
    - -essentials.nick.others
    - essentials.realname
    - essentials.seen.banreason
    - essentials.seen.extra
    - -essentials.setwarp
    - essentials.signs.create.*
    - essentials.signs.break.*
    - essentials.spawner
    - essentials.spawner.*
    - -essentials.thunder
    - essentials.time
    - -essentials.time.set
    - essentials.protect.alerts
    - essentials.protect.admin
    - essentials.protect.ownerinfo
    - essentials.ptime
    - essentials.ptime.others
    - essentials.togglejail
    - essentials.top
    - essentials.tp
    - essentials.tp.others
    - essentials.tphere
    - essentials.tppos
    - essentials.tptoggle
    - essentials.unban
    - essentials.unbanip
    - essentials.vanish
    - essentials.vanish.effect
    - essentials.warps.*
    - -essentials.weather
    - essentials.whois
    - -essentials.workbench
    - essentials.world
    - essentials.worlds.*
    - essentials.jail.allow.jails
    - essentials.jail.allow.togglejail
    - -vanish.*
    - vanish.vanish
    - vanish.smokin
    - vanish.nofollow
    - vanish.nopickup
    - vanish.preventincomingdamage
    - vanish.hooks.dynmap.alwayshidden
    - vanish.hooks.essentials.hide
    options:
      rank: '800'
      prefix: '&8[&bMod&8]&7 '
  Admin:
    inheritance:
    - Mod
    permissions:
    - bukkit.broadcast
    - bukkit.broadcast.admin
    - bukkit.command.give
    - bukkit.command.help
    - bukkit.command.kill
    - bukkit.command.list
    - bukkit.command.me
    - -bukkit.command.op
    - -bukkit.command.op.give
    - -bukkit.command.op.take
    - bukkit.command.plugins
    - bukkit.command.reload
    - bukkit.command.save
    - bukkit.command.save.disable
    - bukkit.command.save.enable
    - bukkit.command.save.perform
    - bukkit.command.say
    - bukkit.command.stop
    - bukkit.command.teleport
    - bukkit.command.tell
    - bukkit.command.time
    - bukkit.command.time.add
    - bukkit.command.time.set
    - bukkit.command.version
    - bukkit.command.whitelist
    - bukkit.command.whitelist.add
    - bukkit.command.whitelist.disable
    - bukkit.command.whitelist.enable
    - bukkit.command.whitelist.list
    - bukkit.command.whitelist.reload
    - bukkit.command.whitelist.remove
    - permissions.*
    - -essentials.backup
    - -essentials.essentials
    - -essentials.setspawn
    - -essentials.reloadall
    - -essentials.plugin
    - essentials.*
    - worldedit.*
    - vanish.silentjoin
    - vanish.silentquit
    - vanish.silentchestsI need 
    options:
      rank: '700'
      prefix: '&8[&eAdmin&8]&7 '
  
  Owner:
    inheritance:
    - Admin
    options:
      rank: '1'
      prefix: '&8[&cOwner&8]&7 '
Technician:
    inheritance:
    - Admin
    options:
    rank : '10'
      prefix: '&8[&aTechnician&8]&7 '
