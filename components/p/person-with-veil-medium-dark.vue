<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ildGWhe)"><path fill="url(#islCJXb)" class="eyq-j4rfj"/><path fill="url(#ioIWxld)" class="eyq-j4rfj"/><path fill="url(#iEv1sxf)" class="eyq-j4rfj"/></g><g filter="url(#iXvptzy)"><path fill="url(#ivbEkQN)" class="jfws982cr"/></g><path fill="url(#iVTY5Sb)" class="b59_i1b1o"/><path fill="url(#iA1j6ff)" class="b59_i1b1o"/><path fill="url(#iKuXPIb)" class="b59_i1b1o"/><path fill="url(#i5iuZHc)" class="b59_i1b1o"/><g filter="url(#iKnWTre)"><path class="fa0nsvbse"/></g><g filter="url(#iIOZlLb)"><path class="zsj5_9a3c"/></g><g filter="url(#im6M7lc)"><path fill="url(#im2xpRd)" class="gcwzfgbdr"/><path fill="url(#iTArIbd)" class="gcwzfgbdr"/><path fill="url(#ifvytLd)" class="gcwzfgbdr"/></g><g filter="url(#iVrCZtc)"><path fill="url(#ivNQXye)" class="ujg3-bcoe"/><path fill="url(#ifVGqfd)" class="ujg3-bcoe"/><path fill="url(#iYt3myd)" class="ujg3-bcoe"/></g><g filter="url(#iJacfRb)"><path fill="url(#iR4jJfd)" class="vtlqp6_0b"/><path fill="url(#iV5fUOc)" class="vtlqp6_0b"/><path fill="url(#ic2YNxe)" class="vtlqp6_0b"/><path fill="url(#iRe9Mge)" class="vtlqp6_0b"/><path fill="url(#imNexrb)" class="vtlqp6_0b"/></g><path fill="url(#i3gw0le)" class="jt0rkibcj"/><path fill="url(#iIOh4ud)" class="jt0rkibcj"/><g filter="url(#ivDrTOb)"><path class="l0czh6bkd"/></g><g filter="url(#iWPIgbd)"><path fill="url(#ihzztUb)" class="i3z4dnj1i"/><path fill="url(#inXVgmc)" class="i3z4dnj1i"/></g><g filter="url(#iEFx9fb)"><path fill="url(#iJ9tQcQ)" class="y_-nyz7qb"/><path fill="url(#ihiLRfd)" class="y_-nyz7qb"/></g><circle fill="url(#iHVMpMg)" class="vl91zwoht"/><circle fill="url(#i3U4Ukc)" class="vl91zwoht"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.399)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.399)" class="movji7bnz"/><circle fill="url(#indWxHb)" class="uuvm0cbel"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.457)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.457)" class="movji7bnz"/><path fill="url(#iGaC8Ub)" class="cf6_ffx9f"/><g filter="url(#if7eoGb)"><path class="xy2hs8s1u"/><path fill="url(#irFI0gb)" class="ct7mdhn7n"/><path fill="url(#iqY51Dc)" class="ct7mdhn7n"/><path fill="url(#ipNad4d)" class="ct7mdhn7n"/><path fill="url(#iUDmEOu)" class="ct7mdhn7n"/><path fill="url(#iQBxcQo)" class="ct7mdhn7n"/></g><path fill="url(#i4LXZSc)" class="gob_x5bhm"/><g filter="url(#i1aRSte)"><path class="afbwhdcra"/><path fill="url(#in4gUjb)" class="o29dz2isc"/><path fill="url(#iVLocse)" class="o29dz2isc"/></g><g filter="url(#ikBVSxc)"><path class="a00kit5sj"/><path fill="url(#iPtVjEc)" class="q4l6o8wsh"/><path fill="url(#irdANWc)" class="q4l6o8wsh"/><path fill="url(#i3ONp1q)" class="q4l6o8wsh"/><path fill="url(#iZUiyFb)" class="q4l6o8wsh"/><path fill="url(#imxLKpc)" class="q4l6o8wsh"/></g><g filter="url(#iObs6ge)"><path fill="url(#iraSsMe)" clip-rule="evenodd" class="wjlbdbb9g"/></g><g filter="url(#iNpTDvc)"><path class="pq27blymw"/></g><g filter="url(#iXqgmJb)"><path fill="url(#iGgANae)" class="g5ilm9bus"/><path fill="url(#iILYo4b)" class="g5ilm9bus"/></g><g filter="url(#iuEBlsc)"><path stroke="url(#iXVKMPb)" class="mhejshymi"/></g><g filter="url(#iukLcke)"><path stroke="url(#i343mgd)" class="y1diaublm"/></g><g filter="url(#i8NKWmN)"><path stroke="url(#i6Fz0Td)" class="f26dbtbnd"/></g><g filter="url(#iHjDmYd)"><path stroke="url(#iqubFtd)" class="w-m7nbbyp"/></g><path fill="url(#iYdN0Ub)" class="m_ze7_bry"/><path fill="url(#iV5T9uQ)" class="gib0msbqk"/><g filter="url(#iQ3ZFQM)"><path fill="url(#idbqP0b)" class="whr7lob7j"/><path fill="url(#iwBDyBb)" class="whr7lob7j"/></g><path fill="url(#iV5Vcie)" class="whr7lob7j"/><path fill="url(#iqZpZxe)" class="whr7lob7j"/><path fill="url(#iniHfme)" class="whr7lob7j"/><path fill="url(#i9WYnrc)" class="whr7lob7j"/><path fill="url(#i0GgeTV)" class="whr7lob7j"/><path fill="url(#iAk86cc)" class="whr7lob7j"/><path fill="url(#iB2oaLb)" class="whr7lob7j"/><g filter="url(#i9qmSIS)"><path class="lhnrnyb2a"/></g><g filter="url(#iXUT5Ib)"><path class="no0rycbde"/><path fill="url(#iaZmSTc)" class="y855vmb4p"/><path fill="url(#ifaMJ4d)" class="y855vmb4p"/><path fill="url(#iEYjCGd)" class="y855vmb4p"/><path fill="url(#iqDxSsV)" class="y855vmb4p"/></g><g filter="url(#iqii9od)"><path fill="url(#i05H8Rc)" class="lomjeubxm"/></g><g filter="url(#ivyMsgd)"><path stroke="url(#itaWUPb)" class="oxtv1lk9j"/></g><path fill="url(#iZFDmDe)" class="zlt3gopou"/><g filter="url(#im1lyzd)"><path fill="url(#iRUdJ3v)" class="izl0i66yg"/><path fill="url(#isOzSLc)" class="izl0i66yg"/><path fill="url(#ixuaCod)" class="izl0i66yg"/><path fill="url(#ifJd5vh)" class="izl0i66yg"/><path fill="url(#i5vgs3d)" class="izl0i66yg"/></g><g filter="url(#iJPCmHe)"><path class="rb2qfcbps"/></g><g filter="url(#ineZmOZ)"><path class="bqqvx6_gt"/></g><g filter="url(#iZD2Vhc)"><path class="k7azdhwly"/><path fill="url(#i9VZ8Qt)" class="dgmzqac2j"/><path fill="url(#iRUFuyd)" class="dgmzqac2j"/></g><g filter="url(#imvEcoe)"><path class="gs-en-u0l"/><path fill="url(#iQ7fqEc)" class="xhbxl3bze"/><path fill="url(#i5unEBe)" class="xhbxl3bze"/></g><path class="x1q1edbdi"/><path fill="url(#isHpJQd)" class="xnxn7_5tz"/><path class="yl-hxybcp"/><g filter="url(#ifayeye)"><path class="vi85dqbae"/><path fill="url(#iUxpYsd)" class="ugxzajs1s"/></g><g filter="url(#iG5L7kb)"><path fill="url(#id4LBuc)" class="vzqcr0bpx"/></g><path class="s35ynvbbl"/><path fill="url(#iGpI53A)" class="ntvgzv36o"/><path class="h6tmhmabt"/><g filter="url(#ig2V4Me)"><path fill="url(#i9DkaJL)" class="ljkpo-b0t"/></g><g filter="url(#ip8N9SE)"><ellipse transform="rotate(-27.914 13.554 9.902)" class="m619t0bjq"/><ellipse fill="url(#iquCPlb)" transform="rotate(-27.914 13.554 9.902)" class="kntkvs5su"/></g><path fill="url(#iRLpKYb)" class="ezur8_b6t"/><path fill="url(#iL3wTKe)" class="ezur8_b6t"/><path fill="url(#isIvnOb)" class="ezur8_b6t"/><path fill="url(#i6yQ5Tc)" class="ezur8_b6t"/><path fill="url(#iC81mFX)" class="h5jot_b7j"/><path fill="url(#ifykX8c)" class="h5jot_b7j"/><g filter="url(#i0OMS7b)"><path fill="url(#idL1bit)" class="kjyprr3hd"/></g><g filter="url(#ik6dIul)"><path fill="url(#iT8iu1S)" class="rr5gzw8nz"/></g><g filter="url(#iwkkENc)"><path class="rlp7-vb_u"/></g><g filter="url(#i00Qwec)"><path class="cj4yqhcxf"/></g><g filter="url(#io09EWZ)"><path class="ty9lniinq"/></g><g filter="url(#iH53qsz)"><path fill="url(#iyeotGk)" clip-rule="evenodd" class="l1wcqp64v"/><path fill="url(#i5ziYRQ)" clip-rule="evenodd" class="l1wcqp64v"/></g><defs><radialGradient id="ioIWxld" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.83 7.015)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="iEv1sxf" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.621)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iVTY5Sb" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.153 15.728)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="iKuXPIb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.996)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i5iuZHc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.153)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iTArIbd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.792)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="ifvytLd" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.639 14.625)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="ifVGqfd" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.762 27.293)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iYt3myd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.855)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iR4jJfd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.77323 -2.8082 3.94394 -10.91704 21.531 21.574)" gradientUnits="userSpaceOnUse"><stop class="wso8oqi8u"/><stop offset="1" class="n50qojbrc"/></radialGradient><radialGradient id="iV5fUOc" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.728 16.623)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="e7aooyb9w"/><stop offset="1" class="t9sj0nb-w"/></radialGradient><radialGradient id="ic2YNxe" cx="0" cy="0" r="1" gradientTransform="rotate(167.545 7.092 9.224)scale(4.44166 1.16057)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="xnros5bvd"/><stop offset="1" class="jn8k7gbea"/></radialGradient><radialGradient id="iRe9Mge" cx="0" cy="0" r="1" gradientTransform="rotate(-143.653 14.52 6.695)scale(.91393 .73652)" gradientUnits="userSpaceOnUse"><stop class="p7lh-mbjd"/><stop offset="1" class="a0i9ffblh"/></radialGradient><radialGradient id="imNexrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.67275 0 14.336 16.69)" gradientUnits="userSpaceOnUse"><stop class="y_9xrnb_b"/><stop offset="1" class="fyyy25bfx"/></radialGradient><radialGradient id="i3gw0le" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.716 35.88)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="inXVgmc" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.162 4.906)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="ihiLRfd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.292)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iHVMpMg" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.317 11.795)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="i3U4Ukc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.422 14.59)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="indWxHb" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.353 12.65)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="iGaC8Ub" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.359 19.36)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="irFI0gb" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.28 20.215)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iqY51Dc" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.481 22.996)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="ipNad4d" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.17 9.217)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iUDmEOu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.277 24.793)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="iQBxcQo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.573)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="i4LXZSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.793)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="in4gUjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.7)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iVLocse" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.713)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iPtVjEc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.278)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="irdANWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.965)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iraSsMe" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.311 16.628)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iGgANae" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.388 23.839)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iILYo4b" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.226)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="iYdN0Ub" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.86 20.847)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iV5T9uQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.47647 .46403 -1.43157 4.55499 9.95 12.346)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="idbqP0b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.815 10.914)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iwBDyBb" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.543 8.165)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iqZpZxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.6301 9.44111 0 15.989 17.304)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="ese68vbcc"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="iniHfme" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.454 9.601)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="i9WYnrc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.695 -2.054)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="i0GgeTV" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 19.44 11.902)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iAk86cc" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.215 8.181)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iB2oaLb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.136 13.81)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="ifaMJ4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.473 12.274)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iqDxSsV" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.59 11.705)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iZFDmDe" cx="0" cy="0" r="1" gradientTransform="matrix(2.18199 -1.07272 4.31584 8.77868 15.516 14.537)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="isOzSLc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.777 8.021)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="ixuaCod" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 15.316 -6.252)scale(2.51513 4.45632)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="ifJd5vh" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 20.114 3.055)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="i5vgs3d" cx="0" cy="0" r="1" gradientTransform="matrix(.67168 1.19822 -2.77451 1.5553 15.102 1.463)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="i9VZ8Qt" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.26 3.722)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iRUFuyd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.241 -5.762)scale(6.02662 6.67688)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iQ7fqEc" cx="0" cy="0" r="1" gradientTransform="matrix(2.67872 -2.55217 4.67237 4.90406 18.64 7.536)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="i5unEBe" cx="0" cy="0" r="1" gradientTransform="matrix(3.24822 .37966 -.15896 1.35997 17.755 6.06)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="isHpJQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 18.189 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iUxpYsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.96 10.082)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGpI53A" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.825 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iquCPlb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49409 .5939 -.0093 13.539 10.216)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iL3wTKe" cx="0" cy="0" r="1" gradientTransform="matrix(.62853 2.24328 -2.14027 .59967 20.625 10.012)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="isIvnOb" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.985 10.556)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="i6yQ5Tc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.099 10.729)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="ifykX8c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.091 10.653)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="idL1bit" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.092 10.655)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="i5ziYRQ" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.67 8.583)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="ildGWhe" width="21.944" height="26.818" x="4.962" y="3.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="iXvptzy" width="12.631" height="14.916" x="9.484" y="8.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/><feGaussianBlur result="effect2_foregroundBlur_4002_3412" stdDeviation=".05"/></filter><filter id="iKnWTre" width="5.874" height="5.537" x="6.993" y="23.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".5"/></filter><filter id="iIOZlLb" width="4.98" height="4.054" x="18.51" y="24.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".5"/></filter><filter id="im6M7lc" width="2.973" height="2.006" x="21.47" y="23.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="iVrCZtc" width="3.281" height="2" x="20.468" y="25.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="iJacfRb" width="13.965" height="11.381" x="9.149" y="12.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.286275 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="ivDrTOb" width="10.996" height="6.432" x="11.932" y="21.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".5"/></filter><filter id="iWPIgbd" width="2.973" height="2.006" x="7.658" y="23.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="iEFx9fb" width="3.266" height="2" x="8.366" y="25.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="if7eoGb" width="6.218" height="6.789" x="8.343" y="19.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3412" result="effect2_innerShadow_4002_3412"/></filter><filter id="i1aRSte" width="6.218" height="6.639" x="17.574" y="19.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3412" result="effect2_innerShadow_4002_3412"/></filter><filter id="ikBVSxc" width="6.702" height="6.417" x="12.683" y="20.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="iObs6ge" width="6.703" height="6.517" x="12.633" y="20.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".15"/></filter><filter id="iNpTDvc" width="3.2" height="3.2" x="14.271" y="22.659" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".25"/></filter><filter id="iXqgmJb" width="2.35" height="2.35" x="14.893" y="23.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="iuEBlsc" width="1.458" height="2.505" x="15.848" y="20.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".125"/></filter><filter id="iukLcke" width="1.723" height="1.924" x="16.94" y="24.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".125"/></filter><filter id="i8NKWmN" width="1.368" height="2.217" x="18.104" y="22.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".125"/></filter><filter id="iHjDmYd" width="3.55" height="1.942" x="15.171" y="17.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".25"/></filter><filter id="iQ3ZFQM" width="11.22" height="12.542" x="10.944" y="4.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3412" result="effect2_innerShadow_4002_3412"/></filter><filter id="i9qmSIS" width="3.747" height="4.9" x="13.992" y="9.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".5"/></filter><filter id="iXUT5Ib" width="2.277" height="3.3" x="14.868" y="9.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".1"/></filter><filter id="iqii9od" width="2.277" height="3.3" x="14.868" y="9.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".1"/></filter><filter id="ivyMsgd" width="3.718" height="1.573" x="14.148" y="13.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".05"/></filter><filter id="im1lyzd" width="12.873" height="8.356" x="9.571" y="1.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3412" result="effect2_innerShadow_4002_3412"/></filter><filter id="iJPCmHe" width="2.339" height="1.19" x="17.596" y="7.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="ineZmOZ" width="2.339" height="1.176" x="12.34" y="7.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><filter id="iZD2Vhc" width="6.584" height="5.992" x="9.926" y="2.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/><feGaussianBlur result="effect2_foregroundBlur_4002_3412" stdDeviation=".125"/></filter><filter id="imvEcoe" width="6.319" height="5.711" x="15.848" y="3.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".125"/></filter><filter id="ifayeye" width=".787" height=".696" x="17.455" y="9.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".05"/></filter><filter id="iG5L7kb" width=".891" height=".913" x="18.295" y="9.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".1"/></filter><filter id="ig2V4Me" width=".986" height="1.04" x="13.852" y="9.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".1"/></filter><filter id="ip8N9SE" width=".913" height=".704" x="13.097" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".05"/></filter><filter id="i0OMS7b" width="1.329" height="2.379" x="9.926" y="9.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".125"/></filter><filter id="ik6dIul" width="1.947" height="2.903" x="20.45" y="9.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".25"/></filter><filter id="iwkkENc" width="2.205" height=".961" x="12.359" y="7.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".1"/></filter><filter id="i00Qwec" width="2.205" height=".961" x="17.638" y="7.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".1"/></filter><filter id="io09EWZ" width="5.266" height="3.005" x="16.886" y="3.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3412" stdDeviation=".375"/></filter><filter id="iH53qsz" width="15.448" height="4.54" x="8.283" y="2.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3412"/></filter><linearGradient id="islCJXb" x1="26.906" x2="11.7" y1="11.496" y2="21.496" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="ivbEkQN" x1="20.7" x2="10.387" y1="17.402" y2="17.402" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iA1j6ff" x1="14.887" x2="14.887" y1="30.871" y2="29.59" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="im2xpRd" x1="23.649" x2="21.867" y1="25.794" y2="24.384" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ivNQXye" x1="22.95" x2="21.169" y1="27.377" y2="25.683" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iIOh4ud" x1="12.653" x2="13.255" y1="29.262" y2="28.918" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="ihzztUb" x1="7.856" x2="9.361" y1="24.278" y2="26.098" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iJ9tQcQ" x1="9.062" x2="10.843" y1="27.377" y2="25.692" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="i3ONp1q" x1="14.919" x2="16.7" y1="27.141" y2="22.871" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iZUiyFb" x1="13.356" x2="16.981" y1="22.903" y2="23.59" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="imxLKpc" x1="17.231" x2="16.325" y1="26.903" y2="25.153" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iXVKMPb" x1="16.477" x2="16.477" y1="20.824" y2="22.832" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="i343mgd" x1="17.286" x2="18.153" y1="24.879" y2="26.082" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="i6Fz0Td" x1="18.728" x2="18.728" y1="22.411" y2="24.027" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iqubFtd" x1="16.132" x2="20.117" y1="19.022" y2="17.851" gradientUnits="userSpaceOnUse"><stop class="dg0-lwyyf"/><stop offset="1" class="d94uojbbb"/></linearGradient><linearGradient id="iV5Vcie" x1="21.164" x2="18.635" y1="12.6" y2="12.6" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iaZmSTc" x1="16.845" x2="16.007" y1="11.588" y2="11.623" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iEYjCGd" x1="16.007" x2="16.007" y1="12.728" y2="12.263" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="i05H8Rc" x1="16.007" x2="16.007" y1="9.696" y2="11.258" gradientUnits="userSpaceOnUse"><stop class="nz0j9tb8x"/><stop offset="1" class="g0jzi1dsv"/></linearGradient><linearGradient id="itaWUPb" x1="14.805" x2="15.124" y1="14.298" y2="13.464" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iRUdJ3v" x1="22.859" x2="11.247" y1="5.251" y2="5.251" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="id4LBuc" x1="18.967" x2="18.653" y1="10.052" y2="10.245" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i9DkaJL" x1="14.569" x2="14.255" y1="10.052" y2="10.245" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iRLpKYb" x1="22.443" x2="21.236" y1="10.079" y2="12.255" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iC81mFX" x1="10.157" x2="11.616" y1="10.783" y2="10.655" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iT8iu1S" x1="21.423" x2="21.423" y1="9.696" y2="11.6" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="iyeotGk" x1="20.481" x2="8.544" y1="3.653" y2="7.34" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-veil-medium-dark" /></template>
<style>
.a00kit5sj {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.174c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.373-.884 1.493l-.457.101a.05.05 0 0 0-.03.078l.307.423c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.413a.05.05 0 0 0-.081.002l-.242.376c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.527a.05.05 0 0 0-.032-.077l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.a0i9ffblh {
  stop-color: var(--svg-color--7c4f3f, #7C4F3F);
  stop-opacity: 0;
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.afbwhdcra {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.762c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.111-.117-.036c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.632c-.044.107-.088.204-.132.31c-.111.293-.303.84-.336 1.135c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b59_i1b1o {
  d: path("M27 29.934v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.559 5 23.734 5 28.934v1z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bqqvx6_gt {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.596 7.826a2.77 2.77 0 0 1 1.739-.36a.277.277 0 0 1-.067.55a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cf6_ffx9f {
  d: path("m11.186 26.303l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.19-.717.059-.797.239c-.3.82-.081 2.136.085 3.001z");
}

.cj4yqhcxf {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.568 8.059c-.257-.185-.898-.51-1.655-.382");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.ct7mdhn7n {
  d: path("M8.528 22.762c-.076-.156-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.634c.099.12.144.111.117-.036c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.632l.133.31c.111.293.303.84.336 1.135c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
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

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dg0-lwyyf {
  stop-color: var(--svg-color--98766e, #98766E);
}

.dgmzqac2j {
  d: path("m16.24 5.298l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.893v1.485z");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
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

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e7aooyb9w {
  stop-color: var(--svg-color--825d5b, #825D5B);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.ese68vbcc {
  stop-color: var(--svg-color--683640, #683640);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.eyq-j4rfj {
  d: path("M5.062 16.434c0-8.813 4.89-13.22 10.922-13.22s10.922 4.22 10.922 13.22v13.5H5.062z");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.ezur8_b6t {
  d: path("M20.929 12.255q.101-1.595.184-3.192a1.61 1.61 0 0 1-.184 3.192");
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

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyyy25bfx {
  stop-color: var(--svg-color--7b5852, #7B5852);
  stop-opacity: 0;
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g0jzi1dsv {
  stop-color: var(--svg-color--855b55, #855B55);
  stop-opacity: 0;
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g5ilm9bus {
  d: path("M15.993 25.226a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.gcwzfgbdr {
  d: path("M21.48 25.296c.063-.898.843-1.585 1.721-1.534l.99.059c.121 0 .162.158.149.207c-.176.967-.961 1.703-2 1.633l-.768-.098a.11.11 0 0 1-.102-.117z");
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gib0msbqk {
  d: path("M11.146 12.164a1.64 1.64 0 0 1-.905-.309v.931c0 .894.532 1.69 1.341 2.02a4.1 4.1 0 0 1-.346-1.18z");
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gob_x5bhm {
  d: path("m20.799 26.303l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.19.718.059.798.239c.3.82.081 2.136-.085 3.001z");
}

.gs-en-u0l {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.22 8.565l-.03-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.672-1.706 1.65-1.488c.94.209 2.005.558 2.816 1.088c1.744 1.137 1.53 3.12.613 4.085");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h5jot_b7j {
  d: path("M10.963 9.05a1.62 1.62 0 0 0-1.393 1.6c0 .859.673 1.56 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.h6tmhmabt {
  fill: var(--svg-color--000, #000);
  d: path("M14.334 10.414a.51.51 0 0 0-.511-.512a.51.51 0 0 0-.455.747h.905a.5.5 0 0 0 .061-.235");
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
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

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.izl0i66yg {
  d: path("M20.862 4.27a2.33 2.33 0 0 1 1.268 1.052a2.37 2.37 0 0 1-.107 2.526a1.56 1.56 0 0 0-.27.875V9.91a1.7 1.7 0 0 0-.667-.268l.078-1.607a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.615-.418h-1.273c-1.845 0-3.341 1.512-3.341 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.35 2.35 0 0 1 1.299-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.281-.118.589-.188.912-.188c.844 0 1.581.456 1.99 1.132c.307.51.79.88 1.352 1.073");
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

.jt0rkibcj {
  d: path("m13.196 29.933l-2.547-3.837l5.25-3.475l5.828 2.91l-2.922 4.402z");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k7azdhwly {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.24 5.298l-.067-.137a.66.66 0 0 0-.615-.418h-1.273c-1.846 0-3.341 1.512-3.341 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.141-.097.26-.18.331-.253l.1-.105c.35-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.472.011.806.42.806.893v1.485z");
}

.kjyprr3hd {
  d: path("M10.922 9.716a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.kntkvs5su {
  cx: 13.554px;
  cy: 9.902px;
  rx: 0.39px;
  ry: 0.197px;
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
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

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhnrnyb2a {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.606 10.395l-.591 1.839c-.101.378.141.756.484.756h.732c.343 0 .585-.384.484-.756l-.494-1.839c-.106-.407-.505-.407-.616 0");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljkpo-b0t {
  d: path("M14.639 10.308c0-.288-.235-.48-.298-.538l-.289.278l.178.362z");
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lomjeubxm {
  d: path("m15.625 10.002l-.532 1.838c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.838c-.115-.408-.646-.408-.766 0");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m_ze7_bry {
  d: path("M20.868 12.164c.335-.01.65-.124.905-.309v.931c0 .894-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
}

.m619t0bjq {
  cx: 13.554px;
  cy: 9.902px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
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

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
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

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.no0rycbde {
  fill: var(--svg-color--7b514f, #7B514F);
  d: path("m15.625 10.199l-.532 1.838c-.108.378.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.ntvgzv36o {
  d: path("M13.823 9.52a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.nz0j9tb8x {
  stop-color: var(--svg-color--855b55, #855B55);
}

.o29dz2isc {
  d: path("M23.457 22.762c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.111-.117-.036c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.632c-.044.107-.088.204-.132.31c-.111.293-.303.84-.336 1.135c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oxtv1lk9j {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.656 13.415a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.001c-.39.203-.85.32-1.351.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
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

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pq27blymw {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.36a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q4l6o8wsh {
  d: path("M12.712 23.174c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.373-.884 1.493l-.457.101a.05.05 0 0 0-.03.078l.307.423c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.413a.05.05 0 0 0-.081.002l-.242.376c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.527a.05.05 0 0 0-.032-.077l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
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

.rb2qfcbps {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.74 7.935a1.85 1.85 0 0 0-.688-.412c-.304-.096-.685-.121-1.212-.057a.277.277 0 0 0 .067.55c.481-.058.776-.028.979.036c.198.063.332.164.49.3a.277.277 0 1 0 .364-.417");
}

.rlp7-vb_u {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.634 8.105c.257-.185.897-.51 1.655-.382");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rr5gzw8nz {
  d: path("M20.95 11.6q.058-.953.11-1.904a.956.956 0 0 1-.11 1.904");
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.s35ynvbbl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.616 9.249c-.653 0-1.205.45-1.355 1.059c-.045.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t9sj0nb-w {
  stop-color: var(--svg-color--825d5b, #825D5B);
  stop-opacity: 0;
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.ty9lniinq {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.2 5.254h-2.081a.483.483 0 1 1 .077-.961c.54.086 1.257.206 1.737.325c1.086.269 1.385.797 1.47 1.174a1.51 1.51 0 0 0-1.203-.538");
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ugxzajs1s {
  d: path("M18.125 9.71c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.ujg3-bcoe {
  d: path("M20.61 25.809c.678-.6 1.716-.536 2.297.112l.69.734c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
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

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vi85dqbae {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.125 9.71c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.vl91zwoht {
  cx: 9.168px;
  cy: 20.5px;
  r: 0.762px;
}

.vtlqp6_0b {
  d: path("M9.15 20.466a11.2 11.2 0 0 1 4.31-2.047c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.519");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vzqcr0bpx {
  d: path("M18.986 10.296a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-m7nbbyp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.847c.395.01 1.357-.063 2.05-.442");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.whr7lob7j {
  d: path("M11.182 13.679a3.916 3.916 0 0 0 3.886 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.884.237-3.76.324-5.643a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.563-2.212-1.442a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.wjlbdbb9g {
  fill-rule: evenodd;
  d: path("M13.709 24.337a.913.913 0 0 1-.753-1.108a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.302l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.56a.3.3 0 0 0 .396.285l.551-.187l.007-.003c.516-.194 1.023.046 1.16.559c.14.532-.183 1.093-.687 1.183l-.466.103a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.383l-.005.009a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.336l.005-.006l.362-.533a.3.3 0 0 0-.196-.464l-.369-.066z");
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wso8oqi8u {
  stop-color: var(--svg-color--946c5d, #946C5D);
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.x1q1edbdi {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.398 9.249c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.227-.271a1.4 1.4 0 0 1 1.37-1.128");
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xhbxl3bze {
  d: path("m21.22 8.565l-.03-.631c-.01-.764-.641-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.672-1.706 1.65-1.488c.94.209 2.005.558 2.816 1.088c1.744 1.137 1.53 3.12.613 4.085");
}

.xnros5bvd {
  stop-color: var(--svg-color--6a3842, #6A3842);
}

.xnxn7_5tz {
  d: path("M18.191 9.52a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xy2hs8s1u {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.762c-.076-.156-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.634c.099.12.144.111.117-.036c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.632l.133.31c.111.293.303.84.336 1.135c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.y_-nyz7qb {
  d: path("M11.39 25.809c-.678-.6-1.716-.536-2.298.112l-.69.734c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.y_9xrnb_b {
  stop-color: var(--svg-color--7b5852, #7B5852);
}

.y1diaublm {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.793l.907 1.18");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.y855vmb4p {
  d: path("m15.625 10.199l-.532 1.838c-.108.378.152.757.52.757h.787c.369 0 .63-.384.52-.757l-.53-1.838c-.115-.407-.646-.407-.766 0");
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yl-hxybcp {
  fill: var(--svg-color--000, #000);
  d: path("M17.68 10.414a.51.51 0 0 1 .511-.512a.51.51 0 0 1 .454.747h-.904a.46.46 0 0 1-.06-.235");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zlt3gopou {
  d: path("M16.007 13.81c-.508 0-.985-.12-1.386-.328c-.136-.07-.284.084-.197.209c.335.507.918.846 1.583.846s1.248-.339 1.583-.846c.087-.13-.06-.28-.198-.21a3 3 0 0 1-1.385.329");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zsj5_9a3c {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.974c.78-.46 1.787-.2 2.235.546l.538.851c.048.079.043.217-.074.262c-1 .38-2.053.104-2.561-.77l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
