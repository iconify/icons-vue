<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iueRVdW)"><path fill="url(#islCJXb)" class="eyq-j4rfj"/><path fill="url(#ioIWxld)" class="eyq-j4rfj"/><path fill="url(#iEv1sxf)" class="eyq-j4rfj"/></g><g filter="url(#ia25F2d)"><path fill="url(#ivbEkQN)" class="jfws982cr"/></g><path fill="url(#iVTY5Sb)" class="b59_i1b1o"/><path fill="url(#iA1j6ff)" class="b59_i1b1o"/><path fill="url(#iKuXPIb)" class="b59_i1b1o"/><path fill="url(#i5iuZHc)" class="b59_i1b1o"/><g filter="url(#ieMIIUd)"><path class="fa0nsvbse"/></g><g filter="url(#ifzIEce)"><path class="zsj5_9a3c"/></g><g filter="url(#izZvMLc)"><path fill="url(#im2xpRd)" class="gcwzfgbdr"/><path fill="url(#iTArIbd)" class="gcwzfgbdr"/><path fill="url(#ifvytLd)" class="gcwzfgbdr"/></g><g filter="url(#i9mhhKl)"><path fill="url(#ivNQXye)" class="ujg3-bcoe"/><path fill="url(#ifVGqfd)" class="ujg3-bcoe"/><path fill="url(#iYt3myd)" class="ujg3-bcoe"/></g><g filter="url(#iJdBQze)"><path fill="url(#iR4jJfd)" class="vtlqp6_0b"/><path fill="url(#iV5fUOc)" class="vtlqp6_0b"/><path fill="url(#ic2YNxe)" class="vtlqp6_0b"/><path fill="url(#iRe9Mge)" class="vtlqp6_0b"/><path fill="url(#imNexrb)" class="vtlqp6_0b"/></g><path fill="url(#i3gw0le)" class="jt0rkibcj"/><path fill="url(#iIOh4ud)" class="jt0rkibcj"/><g filter="url(#i5fWEic)"><path class="l0czh6bkd"/></g><g filter="url(#i3b3cUb)"><path fill="url(#ihzztUb)" class="i3z4dnj1i"/><path fill="url(#inXVgmc)" class="i3z4dnj1i"/></g><g filter="url(#i8BWP7b)"><path fill="url(#iJ9tQcQ)" class="y_-nyz7qb"/><path fill="url(#ihiLRfd)" class="y_-nyz7qb"/></g><circle fill="url(#iHVMpMg)" class="vl91zwoht"/><circle fill="url(#i3U4Ukc)" class="vl91zwoht"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.399)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.399)" class="movji7bnz"/><circle fill="url(#indWxHb)" class="uuvm0cbel"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.457)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.457)" class="movji7bnz"/><path fill="url(#iGaC8Ub)" class="cf6_ffx9f"/><g filter="url(#iwp9dDz)"><path class="xy2hs8s1u"/><path fill="url(#irFI0gb)" class="ct7mdhn7n"/><path fill="url(#iqY51Dc)" class="ct7mdhn7n"/><path fill="url(#ipNad4d)" class="ct7mdhn7n"/><path fill="url(#iUDmEOu)" class="ct7mdhn7n"/><path fill="url(#iQBxcQo)" class="ct7mdhn7n"/></g><path fill="url(#i4LXZSc)" class="gob_x5bhm"/><g filter="url(#iVyKl0E)"><path class="afbwhdcra"/><path fill="url(#in4gUjb)" class="o29dz2isc"/><path fill="url(#iVLocse)" class="o29dz2isc"/></g><g filter="url(#ijuX40b)"><path class="a00kit5sj"/><path fill="url(#iPtVjEc)" class="q4l6o8wsh"/><path fill="url(#irdANWc)" class="q4l6o8wsh"/><path fill="url(#i3ONp1q)" class="q4l6o8wsh"/><path fill="url(#iZUiyFb)" class="q4l6o8wsh"/><path fill="url(#imxLKpc)" class="q4l6o8wsh"/></g><g filter="url(#iJdYnOb)"><path fill="url(#iraSsMe)" clip-rule="evenodd" class="wjlbdbb9g"/></g><g filter="url(#iKpwuVb)"><path class="pq27blymw"/></g><g filter="url(#iXofJEd)"><path fill="url(#iGgANae)" class="g5ilm9bus"/><path fill="url(#iILYo4b)" class="g5ilm9bus"/></g><g filter="url(#i7djyqe)"><path stroke="url(#iXVKMPb)" class="mhejshymi"/></g><g filter="url(#imny7Nc)"><path stroke="url(#i343mgd)" class="y1diaublm"/></g><g filter="url(#i74CwHb)"><path stroke="url(#i6Fz0Td)" class="f26dbtbnd"/></g><g filter="url(#imtsz6q)"><path stroke="url(#iqubFtd)" class="w-m7nbbyp"/></g><g filter="url(#iGh9uJV)"><circle fill="url(#irAG0Kb)" class="szev0i7gs"/></g><g filter="url(#i51gKgd)"><circle fill="url(#i2ZHsWc)" class="on7rg_kex"/></g><g filter="url(#i46C4De)"><circle fill="url(#iMrHPMN)" class="syf84ubpv"/><circle fill="url(#ifIJwXb)" class="syf84ubpv"/></g><g filter="url(#iOdGWCq)"><circle class="kegapnpld"/><circle fill="url(#ibvGOne)" class="rtfw9ub2n"/><circle fill="url(#iAtAs6d)" class="rtfw9ub2n"/></g><g filter="url(#ihMB5Hb)"><path fill="url(#imvSw5c)" class="m9lobrhuc"/><path fill="url(#iOdf9LZ)" class="m9lobrhuc"/><path fill="url(#iBdBK5b)" class="m9lobrhuc"/></g><path fill="url(#ivsJJJc)" class="iz6v732un"/><path fill="url(#iIQ4NVF)" class="iz6v732un"/><path fill="url(#iQboQ9b)" class="iz6v732un"/><path fill="url(#iETo9wE)" class="iz6v732un"/><path fill="url(#ihXnZfc)" class="iz6v732un"/><g filter="url(#iEFeHGe)"><path fill="url(#iYWmfxc)" class="t0agvs6zd"/></g><g filter="url(#imPlrxc)"><path class="d0_bi5bbr"/><path fill="url(#i0iRjue)" class="nmi9jlbwx"/><path fill="url(#iWe6Kob)" class="nmi9jlbwx"/><path fill="url(#i8zw24d)" class="nmi9jlbwx"/><path fill="url(#ieM2a4b)" class="nmi9jlbwx"/></g><g filter="url(#ihwPhAb)"><path class="swjy-wbbd"/></g><g filter="url(#iLB7Qdb)"><path class="afpmfdcej"/><path fill="url(#iZbdL5d)" class="oazlpeb3r"/><path fill="url(#iJi2gpv)" class="oazlpeb3r"/><path fill="url(#ixcKwfc)" class="oazlpeb3r"/><path fill="url(#iIUJGwd)" class="oazlpeb3r"/></g><path stroke="url(#iSzzrbc)" class="ej6jo71xv"/><g filter="url(#irv2z6c)"><path class="e2jvdsbhy"/><path fill="url(#iKbqXCb)" class="l9ejo66yz"/></g><g filter="url(#ifeJaGe)"><path class="omdkle6ce"/><path fill="url(#ihgVcxe)" class="fr9ihlbpz"/></g><path class="szjhcscmy"/><path fill="url(#i2p2Umw)" class="fbbrwcv2u"/><path class="c2vhdtb0w"/><g filter="url(#iILQfgb)"><path class="i5yj20b_n"/><path fill="url(#iulLi8d)" class="aok2_tb7y"/></g><g filter="url(#iX1rUre)"><path fill="url(#iOeDbAe)" class="xy7grnb5u"/></g><path class="sqmqg0k2q"/><path fill="url(#iXzwlPb)" class="sazj-_b2l"/><path class="irv_ek5kl"/><g filter="url(#iCqI7Nd)"><path fill="url(#itAnf5a)" class="a14mmeb4n"/></g><g filter="url(#iz0IEdd)"><ellipse transform="rotate(-27.914 13.54 9.898)" class="fgbnkvb2l"/><ellipse fill="url(#iLPvThc)" transform="rotate(-27.914 13.54 9.898)" class="lzp3t1p-k"/></g><g filter="url(#ilATXwc)"><path stroke="url(#ictrt5a)" class="jtowa00dd"/></g><g filter="url(#iLNmVad)"><path stroke="url(#ihwgsTb)" class="fvw3l6fck"/></g><g filter="url(#ie5brGc)"><path stroke="url(#iRsFgKd)" class="ecqkr81eo"/></g><g filter="url(#iXr4Q7f)"><path fill="url(#iyeotGk)" clip-rule="evenodd" class="l1wcqp64v"/><path fill="url(#i5ziYRQ)" clip-rule="evenodd" class="l1wcqp64v"/></g><defs><radialGradient id="ioIWxld" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.83 7.015)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="iEv1sxf" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.621)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iVTY5Sb" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.153 15.728)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="iKuXPIb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.996)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i5iuZHc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.153)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iTArIbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.792)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="ifvytLd" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.639 14.625)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="ifVGqfd" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.762 27.293)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iYt3myd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.855)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iR4jJfd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.77323 -2.8082 3.94394 -10.91704 21.531 21.574)" gradientUnits="userSpaceOnUse"><stop class="wso8oqi8u"/><stop offset="1" class="n50qojbrc"/></radialGradient><radialGradient id="iV5fUOc" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.728 16.623)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="e7aooyb9w"/><stop offset="1" class="t9sj0nb-w"/></radialGradient><radialGradient id="ic2YNxe" cx="0" cy="0" r="1" gradientTransform="rotate(167.545 7.092 9.224)scale(4.44166 1.16057)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="xnros5bvd"/><stop offset="1" class="jn8k7gbea"/></radialGradient><radialGradient id="iRe9Mge" cx="0" cy="0" r="1" gradientTransform="rotate(-143.653 14.52 6.695)scale(.91393 .73652)" gradientUnits="userSpaceOnUse"><stop class="p7lh-mbjd"/><stop offset="1" class="a0i9ffblh"/></radialGradient><radialGradient id="imNexrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.67275 0 14.336 16.69)" gradientUnits="userSpaceOnUse"><stop class="y_9xrnb_b"/><stop offset="1" class="fyyy25bfx"/></radialGradient><radialGradient id="i3gw0le" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.716 35.88)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="inXVgmc" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.162 4.906)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="ihiLRfd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.292)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iHVMpMg" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.317 11.795)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="i3U4Ukc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.422 14.59)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="indWxHb" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.353 12.65)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="iGaC8Ub" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.359 19.36)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="irFI0gb" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.28 20.215)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iqY51Dc" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.481 22.996)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="ipNad4d" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.17 9.217)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iUDmEOu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.277 24.793)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="iQBxcQo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.573)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="i4LXZSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.793)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="in4gUjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.7)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iVLocse" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.713)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iPtVjEc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.278)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="irdANWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.965)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iraSsMe" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.311 16.628)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iGgANae" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.388 23.839)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iILYo4b" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.226)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="irAG0Kb" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 9.575 10.676)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="ifIJwXb" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 21.14 10.41)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="ibvGOne" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 20.727 11.498)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iAtAs6d" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 20.769 10.676)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iOdf9LZ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 18.346 9.403)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iBdBK5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 13.784 9.537)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iQboQ9b" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.41523 -11.4232 0 15.696 8.9)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="ea1_mzb5k"/><stop offset="1" class="g4wcszb8i"/></radialGradient><radialGradient id="iETo9wE" cx="0" cy="0" r="1" gradientTransform="rotate(-146.07 12.664 5.208)scale(2.07148 1.17905)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="ihXnZfc" cx="0" cy="0" r="1" gradientTransform="matrix(2.59375 -.54454 .34491 1.64288 12.359 17.63)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="i0iRjue" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.46 -10)scale(3.06527 1.47592)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iWe6Kob" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 18.703 4.804)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="i8zw24d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.998 2.066)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="ieM2a4b" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 9.543 8.89)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iIUJGwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 16.326 12.284)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="iKbqXCb" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.78641 .30854 18.443 8.59)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="ihgVcxe" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.7865 .30858 13.29 8.59)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i2p2Umw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 18.18 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iulLi8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.95 10.077)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXzwlPb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 13.812 9.993)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iLPvThc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.79 -1.551)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5ziYRQ" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.67 8.583)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="iueRVdW" width="21.944" height="26.818" x="4.962" y="3.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="ia25F2d" width="12.631" height="14.916" x="9.484" y="8.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/><feGaussianBlur result="effect2_foregroundBlur_4002_3414" stdDeviation=".05"/></filter><filter id="ieMIIUd" width="5.874" height="5.537" x="6.993" y="23.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".5"/></filter><filter id="ifzIEce" width="4.98" height="4.054" x="18.51" y="24.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".5"/></filter><filter id="izZvMLc" width="2.973" height="2.006" x="21.47" y="23.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="i9mhhKl" width="3.281" height="2" x="20.468" y="25.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="iJdBQze" width="13.965" height="11.381" x="9.149" y="12.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.286275 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="i5fWEic" width="10.996" height="6.432" x="11.932" y="21.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".5"/></filter><filter id="i3b3cUb" width="2.973" height="2.006" x="7.658" y="23.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="i8BWP7b" width="3.266" height="2" x="8.366" y="25.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="iwp9dDz" width="6.218" height="6.789" x="8.343" y="19.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3414" result="effect2_innerShadow_4002_3414"/></filter><filter id="iVyKl0E" width="6.218" height="6.639" x="17.574" y="19.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3414" result="effect2_innerShadow_4002_3414"/></filter><filter id="ijuX40b" width="6.702" height="6.417" x="12.683" y="20.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="iJdYnOb" width="6.703" height="6.517" x="12.633" y="20.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".15"/></filter><filter id="iKpwuVb" width="3.2" height="3.2" x="14.271" y="22.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".25"/></filter><filter id="iXofJEd" width="2.35" height="2.35" x="14.893" y="23.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="i7djyqe" width="1.458" height="2.505" x="15.848" y="20.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".125"/></filter><filter id="imny7Nc" width="1.724" height="1.924" x="16.94" y="24.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".125"/></filter><filter id="i74CwHb" width="1.368" height="2.217" x="18.104" y="22.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".125"/></filter><filter id="imtsz6q" width="3.55" height="1.942" x="15.171" y="17.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".25"/></filter><filter id="iGh9uJV" width="3.542" height="3.342" x="9.575" y="9.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="i51gKgd" width="2.992" height="2.992" x="9.75" y="9.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".25"/></filter><filter id="i46C4De" width="3.592" height="3.592" x="19.097" y="8.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="iOdGWCq" width="2.992" height="2.992" x="19.272" y="9.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".25"/></filter><filter id="ihMB5Hb" width="10.383" height="12.189" x="10.835" y="5.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="iEFeHGe" width="8.25" height="7.07" x="14.168" y="3.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation="1"/></filter><filter id="imPlrxc" width="12.614" height="8.551" x="9.692" y="1.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="ihwPhAb" width="3.262" height="4.184" x="14.128" y="9.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".375"/></filter><filter id="iLB7Qdb" width="2.379" height="3.184" x="14.809" y="9.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".125"/></filter><filter id="irv2z6c" width="2.982" height="1.874" x="17.181" y="7.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="ifeJaGe" width="2.982" height="1.874" x="12.029" y="7.024" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><filter id="iILQfgb" width=".787" height=".697" x="17.445" y="9.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".05"/></filter><filter id="iX1rUre" width=".892" height=".914" x="18.285" y="9.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".1"/></filter><filter id="iCqI7Nd" width=".987" height="1.041" x="13.839" y="9.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".1"/></filter><filter id="iz0IEdd" width=".914" height=".705" x="13.084" y="9.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".05"/></filter><filter id="ilATXwc" width="3.101" height="1.682" x="17.035" y="7.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".25"/></filter><filter id="iLNmVad" width="3.179" height="1.739" x="11.811" y="7.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".25"/></filter><filter id="ie5brGc" width="1.008" height="2.271" x="10.828" y="5.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3414" stdDeviation=".125"/></filter><filter id="iXr4Q7f" width="15.448" height="4.54" x="8.283" y="2.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3414"/></filter><linearGradient id="islCJXb" x1="26.906" x2="11.7" y1="11.496" y2="21.496" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="ivbEkQN" x1="20.7" x2="10.387" y1="17.402" y2="17.402" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iA1j6ff" x1="14.887" x2="14.887" y1="30.871" y2="29.59" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="im2xpRd" x1="23.649" x2="21.867" y1="25.794" y2="24.384" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ivNQXye" x1="22.95" x2="21.169" y1="27.377" y2="25.683" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iIOh4ud" x1="12.653" x2="13.255" y1="29.262" y2="28.918" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="ihzztUb" x1="7.856" x2="9.361" y1="24.278" y2="26.098" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iJ9tQcQ" x1="9.062" x2="10.843" y1="27.377" y2="25.692" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="i3ONp1q" x1="14.919" x2="16.7" y1="27.141" y2="22.871" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iZUiyFb" x1="13.356" x2="16.981" y1="22.903" y2="23.59" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="imxLKpc" x1="17.231" x2="16.325" y1="26.903" y2="25.153" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iXVKMPb" x1="16.477" x2="16.477" y1="20.824" y2="22.832" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="i343mgd" x1="17.286" x2="18.153" y1="24.879" y2="26.082" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="i6Fz0Td" x1="18.728" x2="18.728" y1="22.411" y2="24.027" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iqubFtd" x1="16.132" x2="20.117" y1="19.022" y2="17.851" gradientUnits="userSpaceOnUse"><stop class="dg0-lwyyf"/><stop offset="1" class="d94uojbbb"/></linearGradient><linearGradient id="i2ZHsWc" x1="11.246" x2="10.605" y1="10.954" y2="10.954" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="iMrHPMN" x1="21.855" x2="21.036" y1="9.583" y2="12.122" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="imvSw5c" x1="20.038" x2="12.394" y1="11.066" y2="12.205" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="ivsJJJc" x1="10.597" x2="12.48" y1="13.764" y2="13.697" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="iIQ4NVF" x1="20.867" x2="19.81" y1="12.925" y2="12.825" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iYWmfxc" x1="15.466" x2="23.618" y1="8.078" y2="5.159" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="iZbdL5d" x1="15.133" x2="16.072" y1="11.725" y2="11.725" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="iJi2gpv" x1="16.938" x2="15.911" y1="12.048" y2="12.034" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="ixcKwfc" x1="16.193" x2="16.193" y1="12.791" y2="12.218" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="iSzzrbc" x1="14.96" x2="15.396" y1="14.409" y2="13.72" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iOeDbAe" x1="18.958" x2="18.644" y1="10.047" y2="10.24" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itAnf5a" x1="14.556" x2="14.242" y1="10.047" y2="10.24" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ictrt5a" x1="18.973" x2="18.553" y1="7.906" y2="7.046" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ihwgsTb" x1="13.664" x2="12.473" y1="7.778" y2="7.279" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iRsFgKd" x1="11.332" x2="11.332" y1="5.762" y2="7.921" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="iyeotGk" x1="20.481" x2="8.544" y1="3.653" y2="7.34" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-veil-medium-dark" /></template>
<style>
.a00kit5sj {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.174c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.373-.884 1.493l-.457.101a.05.05 0 0 0-.03.078l.307.423c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.413a.05.05 0 0 0-.081.002l-.242.376c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.527a.05.05 0 0 0-.032-.077l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.a0i9ffblh {
  stop-color: var(--svg-color--7c4f3f, #7C4F3F);
  stop-opacity: 0;
}

.a14mmeb4n {
  d: path("M14.626 10.304c0-.289-.235-.481-.298-.54l-.289.28l.178.361z");
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.afbwhdcra {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.762c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.111-.117-.036c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.632c-.044.107-.088.204-.132.31c-.111.293-.303.84-.336 1.135c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.afpmfdcej {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.616 10.39l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.765 0");
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.aok2_tb7y {
  d: path("M18.116 9.705c.063.085-.07.188-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b59_i1b1o {
  d: path("M27 29.934v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.559 5 23.734 5 28.934v1z");
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c2vhdtb0w {
  fill: var(--svg-color--000, #000);
  d: path("M17.67 10.409a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .455.747h-.905a.46.46 0 0 1-.061-.235");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.cf6_ffx9f {
  d: path("m11.186 26.303l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.19-.717.059-.797.239c-.3.82-.081 2.136.085 3.001z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.ct7mdhn7n {
  d: path("M8.528 22.762c-.076-.156-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.634c.099.12.144.111.117-.036c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.632l.133.31c.111.293.303.84.336 1.135c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d0_bi5bbr {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m20.822 4.192l.43.213c.75.374 1.18 1.228 1.02 2.136l-.591 3.043c-.053.314-.26.526-.573.533h-.018s.054-.907.108-1.44c.043-.434-.032-.567-.43-.962c-.215-.213-.376-.534-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427c-1.932 0-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.375.854l-.162.16c-.214.16-.322.48-.322.748c.054.587.108 1.441.108 1.441l-.05-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.074-2.082l.43-.213a8 8 0 0 0 .805-.587l.966-1.015c.59-.533 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.267 1.718-.053 2.362.534l.805.8c.215.268.484.428.806.588");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.d94uojbbb {
  stop-color: var(--svg-color--98766e, #98766E);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dg0-lwyyf {
  stop-color: var(--svg-color--98766e, #98766E);
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2jvdsbhy {
  fill: var(--svg-color--352827, #352827);
  d: path("m19.721 7.953l-.003-.002l-.004-.004l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.158a.534.534 0 0 0 .166 1.055c.398-.063.717.01.935.096a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .68-.825");
}

.e7aooyb9w {
  stop-color: var(--svg-color--825d5b, #825D5B);
}

.ea1_mzb5k {
  stop-color: var(--svg-color--784654, #784654);
  stop-opacity: 0;
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ecqkr81eo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.461 5.86v.899c-.008.148-.07.481-.258.622");
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ej6jo71xv {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.635 13.436c.394.206.863.323 1.363.323c.505 0 .97-.117 1.364-.323a.204.204 0 0 1 .242.04a.19.19 0 0 1 .02.241m-2.989-.28l2.948.253m-2.948-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.221.254m3.21.027l-.041-.027m.041.027l-.041-.027m.041.027a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.027a1.89 1.89 0 0 1-1.584.846a1.9 1.9 0 0 1-1.584-.846m-.042.028l.042-.028m-.042.028l.042-.028");
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.eyq-j4rfj {
  d: path("M5.062 16.434c0-8.813 4.89-13.22 10.922-13.22s10.922 4.22 10.922 13.22v13.5H5.062z");
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f26dbtbnd {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.574c.307.136.83.616.461 1.453");
}

.fa0nsvbse {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.145c.879-.05 1.658.637 1.72 1.534l.009.116c.31.044.61.175.862.398l.107.113a.11.11 0 0 1 .01.15l-.42.583c-.665.762-1.75.833-2.66.27c-.064-.05-.086-.203-.024-.27l.69-.735q.136-.15.302-.26c-.906-.06-1.574-.75-1.735-1.633c-.013-.05.028-.207.15-.207z");
}

.fbbrwcv2u {
  d: path("M18.181 9.516a.893.893 0 0 1 .86 1.128h-1.724a.897.897 0 0 1 .865-1.129");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fgbnkvb2l {
  cx: 13.541px;
  cy: 9.898px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fr9ihlbpz {
  d: path("M12.221 7.954v-.001h.002l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.241-.14.42-.211a2.83 2.83 0 0 1 1.494-.158a.534.534 0 0 1-.166 1.055a1.77 1.77 0 0 0-.935.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.68-.824");
}

.ft5dv1b6b {
  fill: none;
}

.fvw3l6fck {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.436 8.328c.327-.29 1.043-.594 1.929-.453");
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.fyyy25bfx {
  stop-color: var(--svg-color--7b5852, #7B5852);
  stop-opacity: 0;
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g4wcszb8i {
  stop-color: var(--svg-color--683541, #683541);
}

.g5ilm9bus {
  d: path("M15.993 25.226a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.gcwzfgbdr {
  d: path("M21.48 25.296c.063-.898.843-1.585 1.721-1.534l.99.059c.121 0 .162.158.149.207c-.176.967-.961 1.703-2 1.633l-.768-.098a.11.11 0 0 1-.102-.117z");
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gob_x5bhm {
  d: path("m20.799 26.303l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.19.718.059.798.239c.3.82.081 2.136-.085 3.001z");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i3z4dnj1i {
  d: path("M10.52 25.296c-.063-.898-.843-1.585-1.721-1.534l-.99.059c-.121 0-.162.158-.149.207c.176.967.961 1.703 2 1.633l.768-.098a.11.11 0 0 0 .102-.117z");
}

.i5yj20b_n {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.116 9.705c.063.085-.07.188-.221.302s-.263.192-.327.107s.007-.246.159-.359c.15-.113.325-.135.389-.05");
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.irv_ek5kl {
  fill: var(--svg-color--000, #000);
  d: path("M14.322 10.409a.51.51 0 0 0-.512-.512a.51.51 0 0 0-.455.747h.906a.5.5 0 0 0 .06-.235");
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.iz6v732un {
  d: path("M10.835 8.623c0-.267.108-.588.322-.748l.162-.16c.268-.213.375-.534.375-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.471.546.43.961a47 47 0 0 0-.108 1.441h.018l-.266 3.962c-.16 1.772-1.553 3.006-3.213 3.006h-3.214c-1.713 0-3.052-1.234-3.213-3.006c-.14-1.818-.2-3.641-.367-5.456");
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jfws982cr {
  d: path("M9.984 15.856c0-4.854 2.694-7.28 6.016-7.28s6.016 2.323 6.016 7.28v7.435H9.984z");
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jn8k7gbea {
  stop-color: var(--svg-color--693e41, #693E41);
  stop-opacity: 0;
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jt0rkibcj {
  d: path("m13.196 29.933l-2.547-3.837l5.25-3.475l5.828 2.91l-2.922 4.402z");
}

.jtowa00dd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.66 7.809c.43-.076 1.27-.054 1.851.398");
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.kegapnpld {
  cx: 20.768px;
  cy: 10.676px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.l0czh6bkd {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.41c.096.054.144.22.081.349l-.668 1.39c-.181.388-.526.925-.809 1.177c-.687.638-1.466.645-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.324-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.002l-.201.313a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.416l.298-.437a.042.042 0 0 0-.027-.065l-.308-.055a.97.97 0 0 1-.799-1.174a.97.97 0 0 1 1.248-.707l.516.176a.042.042 0 0 0 .055-.043l-.025-.402c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.665.81-1.062v.467c0 .028.028.048.055.039l.458-.156q.112-.042.223-.058l.036-.084l1.043.853c.063-.129.19-.198.295-.152c.711.328.494-.417.288.728c-.022.123.015.13.098.03c.74-.9 1.97-1.695 2.682-1.36");
}

.l1wcqp64v {
  fill-rule: evenodd;
  d: path("M15.972 4.365c-3.812 0-5.694 1.657-6.334 2.38a.775.775 0 0 1-1.16-1.028c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.915 7.54 2.877A.775.775 0 1 1 22.4 6.77c-.735-.758-2.556-2.406-6.428-2.406");
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.l9ejo66yz {
  d: path("m19.721 7.953l-.003-.002l-.004-.004l-.012-.01l-.036-.027a2.6 2.6 0 0 0-.54-.291a2.84 2.84 0 0 0-1.493-.158a.534.534 0 0 0 .166 1.055c.398-.063.717.01.935.096a1.5 1.5 0 0 1 .308.166a.534.534 0 0 0 .68-.825");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lzp3t1p-k {
  cx: 13.541px;
  cy: 9.898px;
  rx: 0.39px;
  ry: 0.197px;
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.m9lobrhuc {
  d: path("m10.894 10.062l.049.002s-.054-.854-.108-1.441c0-.267.108-.588.322-.748l.162-.16c.268-.213.375-.534.375-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.92-.427c1.932 0 3.274.267 3.919.427c.214.053.43.267.43.534v.854c0 .32.16.64.375.854c.503.352.471.546.43.961a47 47 0 0 0-.108 1.441h.018l-.266 3.962c-.16 1.772-1.553 3.006-3.213 3.006h-3.214c-1.713 0-3.052-1.234-3.213-3.006z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mhejshymi {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.027c.324 0 .758.377.758.86v.945");
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.n50qojbrc {
  stop-color: var(--svg-color--734f43, #734F43);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nmi9jlbwx {
  d: path("m20.822 4.192l.43.213c.75.374 1.18 1.228 1.02 2.136l-.591 3.043c-.053.314-.26.526-.573.533h-.018s.054-.907.108-1.44c.043-.434-.032-.567-.43-.962c-.215-.213-.376-.534-.376-.854v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.919-.427c-1.932 0-3.275.267-3.92.427a.52.52 0 0 0-.429.534v.854c0 .32-.107.64-.375.854l-.162.16c-.214.16-.322.48-.322.748c.054.587.108 1.441.108 1.441l-.05-.002a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.322-1.708 1.074-2.082l.43-.213a8 8 0 0 0 .805-.587l.966-1.015c.59-.533 1.45-.694 2.201-.32c.537.16 1.128.16 1.665 0c.805-.267 1.718-.053 2.362.534l.805.8c.215.268.484.428.806.588");
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.o29dz2isc {
  d: path("M23.457 22.762c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.111-.117-.036c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.632c-.044.107-.088.204-.132.31c-.111.293-.303.84-.336 1.135c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.oazlpeb3r {
  d: path("m15.616 10.39l-.532 1.701a.54.54 0 0 0 .52.7h.788a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.378-.646-.378-.765 0");
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.omdkle6ce {
  fill: var(--svg-color--352827, #352827);
  d: path("M12.221 7.954v-.001h.002l.002-.002l.004-.004l.012-.01a2 2 0 0 1 .155-.107c.1-.063.241-.14.42-.211a2.83 2.83 0 0 1 1.494-.158a.534.534 0 0 1-.166 1.055a1.77 1.77 0 0 0-.935.096a1.5 1.5 0 0 0-.308.166a.534.534 0 0 1-.68-.824");
}

.on7rg_kex {
  cx: 11.246px;
  cy: 10.676px;
  r: 0.996px;
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.p7lh-mbjd {
  stop-color: var(--svg-color--7c4f3f, #7C4F3F);
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pq27blymw {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.36a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q4l6o8wsh {
  d: path("M12.712 23.174c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.373-.884 1.493l-.457.101a.05.05 0 0 0-.03.078l.307.423c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.413a.05.05 0 0 0-.081.002l-.242.376c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.527a.05.05 0 0 0-.032-.077l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.rtfw9ub2n {
  cx: 20.768px;
  cy: 10.676px;
  r: 0.996px;
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sazj-_b2l {
  d: path("M13.81 9.516a.893.893 0 0 0-.86 1.128h1.725a1 1 0 0 0 .032-.235a.9.9 0 0 0-.897-.893");
}

.sqmqg0k2q {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.603 9.244c-.654 0-1.206.45-1.356 1.06a.274.274 0 0 0 .268.34h2.233a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.372-1.129");
}

.swjy-wbbd {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.723 10.554l-.821 1.701c-.102.35.142.7.488.7h.738c.346 0 .59-.355.489-.7l-.5-1.7c-.106-.378-.282-.378-.394 0");
}

.syf84ubpv {
  cx: 20.768px;
  cy: 10.676px;
  r: 1.671px;
}

.szev0i7gs {
  cx: 11.246px;
  cy: 10.676px;
  r: 1.671px;
}

.szjhcscmy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.388 9.244c.654 0 1.206.45 1.356 1.06a.274.274 0 0 1-.268.34h-2.232a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.129");
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t0agvs6zd {
  d: path("m19.966 5.046l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.062-.41z");
}

.t9sj0nb-w {
  stop-color: var(--svg-color--825d5b, #825D5B);
  stop-opacity: 0;
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.ujg3-bcoe {
  d: path("M20.61 25.809c.678-.6 1.716-.536 2.297.112l.69.734c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uuvm0cbel {
  cx: 10.18px;
  cy: 21.579px;
  r: 0.762px;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vl91zwoht {
  cx: 9.168px;
  cy: 20.5px;
  r: 0.762px;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vtlqp6_0b {
  d: path("M9.15 20.466a11.2 11.2 0 0 1 4.31-2.047c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.519");
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w-m7nbbyp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.847c.395.01 1.357-.063 2.05-.442");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wjlbdbb9g {
  fill-rule: evenodd;
  d: path("M13.709 24.337a.913.913 0 0 1-.753-1.108a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.302l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.56a.3.3 0 0 0 .396.285l.551-.187l.007-.003c.516-.194 1.023.046 1.16.559c.14.532-.183 1.093-.687 1.183l-.466.103a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.383l-.005.009a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.336l.005-.006l.362-.533a.3.3 0 0 0-.196-.464l-.369-.066z");
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wso8oqi8u {
  stop-color: var(--svg-color--946c5d, #946C5D);
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xnros5bvd {
  stop-color: var(--svg-color--6a3842, #6A3842);
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xy2hs8s1u {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.762c-.076-.156-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.634c.099.12.144.111.117-.036c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.632l.133.31c.111.293.303.84.336 1.135c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.xy7grnb5u {
  d: path("M18.977 10.291a.84.84 0 0 0-.232-.463l-.26.286l.118.228z");
}

.y_-nyz7qb {
  d: path("M11.39 25.809c-.678-.6-1.716-.536-2.298.112l-.69.734c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.y_9xrnb_b {
  stop-color: var(--svg-color--7b5852, #7B5852);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y1diaublm {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.793l.907 1.18");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zsj5_9a3c {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.974c.78-.46 1.787-.2 2.235.546l.538.851c.048.079.043.217-.074.262c-1 .38-2.053.104-2.561-.77l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
