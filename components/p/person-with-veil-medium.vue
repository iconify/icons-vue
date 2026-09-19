<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihUuTEe)"><path fill="url(#islCJXb)" class="eyq-j4rfj"/><path fill="url(#ioIWxld)" class="eyq-j4rfj"/><path fill="url(#iEv1sxf)" class="eyq-j4rfj"/></g><g filter="url(#iWRD0nA)"><path fill="url(#ivbEkQN)" class="jfws982cr"/></g><path fill="url(#iVTY5Sb)" class="b59_i1b1o"/><path fill="url(#iA1j6ff)" class="b59_i1b1o"/><path fill="url(#iKuXPIb)" class="b59_i1b1o"/><path fill="url(#i5iuZHc)" class="b59_i1b1o"/><g filter="url(#i3Zyh7b)"><path class="fa0nsvbse"/></g><g filter="url(#igYHWZJ)"><path class="zsj5_9a3c"/></g><g filter="url(#is8Moib)"><path fill="url(#iXC7Lmd)" class="fv5c-3h7r"/><path fill="url(#iJt1yMe)" class="fv5c-3h7r"/><path fill="url(#iFRXisd)" class="fv5c-3h7r"/></g><g filter="url(#iSo66Bd)"><path fill="url(#ivNQXye)" class="ujg3-bcoe"/><path fill="url(#ifVGqfd)" class="ujg3-bcoe"/><path fill="url(#iYt3myd)" class="ujg3-bcoe"/></g><g filter="url(#izKJgre)"><path fill="url(#ihOartP)" class="vtlqp6_0b"/><path fill="url(#i3wZ4vc)" class="vtlqp6_0b"/><path fill="url(#iBA9Lqc)" class="vtlqp6_0b"/><path fill="url(#i9Jzsdd)" class="vtlqp6_0b"/><path fill="url(#ikD4b6c)" class="vtlqp6_0b"/></g><path fill="url(#i3gw0le)" class="jt0rkibcj"/><path fill="url(#iIOh4ud)" class="jt0rkibcj"/><g filter="url(#it4Y7bv)"><path class="iwey-wb_a"/></g><g filter="url(#isVaWId)"><path fill="url(#iTyFUGe)" class="r4tpvlruj"/><path fill="url(#iekJ1xd)" class="r4tpvlruj"/></g><g filter="url(#iO6NfJb)"><path fill="url(#iJ9tQcQ)" class="y_-nyz7qb"/><path fill="url(#ihiLRfd)" class="y_-nyz7qb"/></g><circle fill="url(#iHVMpMg)" class="vl91zwoht"/><circle fill="url(#i3U4Ukc)" class="vl91zwoht"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.399)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.399)" class="movji7bnz"/><circle fill="url(#indWxHb)" class="uuvm0cbel"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.457)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.457)" class="movji7bnz"/><path fill="url(#iGaC8Ub)" class="cf6_ffx9f"/><g filter="url(#iPZsz3d)"><path class="xy2hs8s1u"/><path fill="url(#irFI0gb)" class="ct7mdhn7n"/><path fill="url(#iqY51Dc)" class="ct7mdhn7n"/><path fill="url(#ipNad4d)" class="ct7mdhn7n"/><path fill="url(#iUDmEOu)" class="ct7mdhn7n"/><path fill="url(#iQBxcQo)" class="ct7mdhn7n"/></g><path fill="url(#i4LXZSc)" class="gob_x5bhm"/><g filter="url(#i0x3x8c)"><path class="afbwhdcra"/><path fill="url(#in4gUjb)" class="o29dz2isc"/><path fill="url(#iVLocse)" class="o29dz2isc"/></g><g filter="url(#iEUlPdc)"><path class="a00kit5sj"/><path fill="url(#iPtVjEc)" class="q4l6o8wsh"/><path fill="url(#irdANWc)" class="q4l6o8wsh"/><path fill="url(#i3ONp1q)" class="q4l6o8wsh"/><path fill="url(#iZUiyFb)" class="q4l6o8wsh"/><path fill="url(#imxLKpc)" class="q4l6o8wsh"/></g><g filter="url(#ilGJtqc)"><path fill="url(#iraSsMe)" clip-rule="evenodd" class="wjlbdbb9g"/></g><g filter="url(#iIGKHqd)"><path class="edcynnb_d"/></g><g filter="url(#iF1htHe)"><path fill="url(#iGgANae)" class="g5ilm9bus"/><path fill="url(#iILYo4b)" class="g5ilm9bus"/></g><g filter="url(#iU5Sn2b)"><path stroke="url(#iXVKMPb)" class="mhejshymi"/></g><g filter="url(#isXruLb)"><path stroke="url(#i343mgd)" class="y1diaublm"/></g><g filter="url(#iqmIIed)"><path stroke="url(#i6Fz0Td)" class="f26dbtbnd"/></g><g filter="url(#idYKqhb)"><path stroke="url(#iXqAzDc)" class="w-m7nbbyp"/></g><path fill="url(#iHv0GHe)" class="acc9bdbvb"/><path fill="url(#iNSFz5c)" class="ehefnubnv"/><g filter="url(#iAu4sLc)"><path fill="url(#irRTHrb)" class="rboc6roet"/><path fill="url(#isORPCc)" class="rboc6roet"/></g><path fill="url(#iLye4Ke)" class="rboc6roet"/><path fill="url(#iWkaZue)" class="rboc6roet"/><path fill="url(#iuPhE1c)" class="rboc6roet"/><path fill="url(#iPHeJ5a)" class="rboc6roet"/><path fill="url(#itFPTLb)" class="rboc6roet"/><path fill="url(#iXv6VQa)" class="rboc6roet"/><path fill="url(#iy78rhb)" class="rboc6roet"/><path fill="url(#iB4ESxd)" class="rboc6roet"/><g filter="url(#i7qdxpc)"><path class="er6xh__hd"/></g><g filter="url(#iw2LW1c)"><path class="e445prfyo"/><path fill="url(#iTgvy4d)" class="reyqluqkr"/><path fill="url(#inp6zNc)" class="reyqluqkr"/><path fill="url(#iAmVkvA)" class="reyqluqkr"/><path fill="url(#iV6tCfc)" class="reyqluqkr"/></g><g filter="url(#igZQYod)"><path fill="url(#ib6HYoe)" class="rbir1vjpi"/></g><g filter="url(#i9Q47Kc)"><path stroke="url(#iBtNSvd)" class="x315_wofb"/></g><path fill="url(#inJLAJb)" class="qc-g9xhzu"/><g filter="url(#istR5sd)"><path fill="url(#iMfivjd)" class="kp9ybz5fn"/></g><path fill="url(#itnj4Vd)" class="kp9ybz5fn"/><path fill="url(#irTaiSd)" class="kp9ybz5fn"/><path fill="url(#iTUkdGX)" class="kp9ybz5fn"/><g filter="url(#iBYnftc)"><path class="gzbijacst"/></g><g filter="url(#iT8MBtb)"><path class="kv4e3-v2a"/></g><g filter="url(#iF5Y36b)"><path class="xvtzdvb_i"/><path fill="url(#iYJMFde)" class="ytgsxobsm"/><path fill="url(#iM4psEd)" class="ytgsxobsm"/></g><g filter="url(#iG9JSTc)"><path class="xne16_jnl"/><path fill="url(#iAznjoe)" class="vcabx4bgj"/><path fill="url(#itzm0Hd)" class="vcabx4bgj"/><path fill="url(#ijxGxsd)" class="vcabx4bgj"/></g><path class="l5m-gut8r"/><path fill="url(#iz2Rgde)" class="s6ho2lbhy"/><path class="setey9z5u"/><g filter="url(#iOltIpe)"><path class="lsfbu9bdl"/><path fill="url(#i5C6Wcd)" class="g5ju3nm-w"/></g><g filter="url(#iFBVwtd)"><path fill="url(#iWcGalb)" class="b4hfjgbtp"/></g><path class="e_5qze5bt"/><path fill="url(#iUOQtjd)" class="j9dx1bb5l"/><path class="n-lindbmp"/><g filter="url(#iRLx7Ib)"><path fill="url(#iLoOf2b)" class="sjnpwht8s"/></g><g filter="url(#i0Lg59c)"><ellipse transform="rotate(-27.914 13.539 9.902)" class="yvs0b-mya"/><ellipse fill="url(#iTkvLJd)" transform="rotate(-27.914 13.539 9.902)" class="kx006679i"/></g><path fill="url(#ifmElMe)" class="mhv-kw2uy"/><path fill="url(#i5Dyhxc)" class="mhv-kw2uy"/><path fill="url(#iu76PLe)" class="mhv-kw2uy"/><path fill="url(#iCdkYWc)" class="mhv-kw2uy"/><path fill="url(#if8mEid)" class="xs57zoclf"/><path fill="url(#iqEYJdc)" class="xs57zoclf"/><g filter="url(#iVrJOQb)"><path fill="url(#ixPB2fd)" class="x009kdzqb"/></g><g filter="url(#iMKoq8d)"><path fill="url(#iWW02WZ)" class="hlt05jbnl"/></g><g filter="url(#iQcDuub)"><path class="x8hqoxpur"/></g><g filter="url(#iULeJ7b)"><path class="fl44_wb9p"/></g><g filter="url(#i9DJ1fb)"><path class="g6q9qacjk"/></g><g filter="url(#iJS5A4b)"><path fill="url(#i7ArLZb)" clip-rule="evenodd" class="jzk7dab5r"/><path fill="url(#i5ziYRQ)" clip-rule="evenodd" class="jzk7dab5r"/></g><defs><radialGradient id="ioIWxld" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.83 7.015)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="iEv1sxf" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.621)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iVTY5Sb" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.153 15.728)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="iKuXPIb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.996)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i5iuZHc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.153)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iJt1yMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.79)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iFRXisd" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.639 14.624)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="ifVGqfd" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.762 27.293)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iYt3myd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.855)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="ihOartP" cx="0" cy="0" r="1" gradientTransform="matrix(-6.95206 -2.46677 3.46444 -9.76378 21.531 21.574)" gradientUnits="userSpaceOnUse"><stop class="qvobj7b6r"/><stop offset="1" class="zrr9gv88m"/></radialGradient><radialGradient id="i3wZ4vc" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.728 16.623)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="shkcotbtg"/><stop offset="1" class="x5158qbnu"/></radialGradient><radialGradient id="iBA9Lqc" cx="0" cy="0" r="1" gradientTransform="rotate(167.545 7.092 9.224)scale(4.44166 1.16057)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="gus-gbb9t"/><stop offset="1" class="uubrgfq8x"/></radialGradient><radialGradient id="i9Jzsdd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07223 -.6455 .5202 -.8641 22.585 20.797)" gradientUnits="userSpaceOnUse"><stop class="ov1bd0bys"/><stop offset="1" class="a0i9ffblh"/><stop offset="1" class="i829wfr2g"/></radialGradient><radialGradient id="ikD4b6c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.67275 0 14.336 16.69)" gradientUnits="userSpaceOnUse"><stop class="ysbaxhbyq"/><stop offset="1" class="x15soc1he"/></radialGradient><radialGradient id="i3gw0le" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.716 35.88)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="iekJ1xd" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.162 4.905)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="ihiLRfd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.292)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iHVMpMg" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.317 11.795)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="i3U4Ukc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.422 14.59)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="indWxHb" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.353 12.65)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="iGaC8Ub" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.359 19.36)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="irFI0gb" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.28 20.215)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iqY51Dc" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.481 22.996)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="ipNad4d" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.17 9.217)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iUDmEOu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.277 24.793)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="iQBxcQo" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.573)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="i4LXZSc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.793)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="in4gUjb" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.7)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iVLocse" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.713)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iPtVjEc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.278)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="irdANWc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.965)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iraSsMe" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.311 16.628)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iGgANae" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.388 23.839)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iILYo4b" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.226)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="iHv0GHe" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.854 20.836)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iNSFz5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.936 12.345)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="irRTHrb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.70503 0 0 -8.32316 18.8 10.914)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="isORPCc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.536 8.161)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iWkaZue" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.9539 -9.89924 0 16.552 5.47)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="zbtz915uf"/><stop offset="1" class="qqmtywb_k"/></radialGradient><radialGradient id="iuPhE1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 18.44 9.6)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="iPHeJ5a" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.687 -2.047)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="itFPTLb" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.525 6.257)scale(8.51289 21.7462)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="iXv6VQa" cx="0" cy="0" r="1" gradientTransform="matrix(3.38579 -2.91647 .86148 1.0001 9.2 8.18)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iy78rhb" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.128 13.802)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="iB4ESxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87159 -1.6732 0 13.777 10.418)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="inp6zNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 16.459 12.274)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iV6tCfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69206 .7501 -1.20547 -2.71927 16.575 11.705)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="inJLAJb" cx="0" cy="0" r="1" gradientTransform="matrix(2.18198 -1.07272 4.31585 8.77866 15.502 14.537)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="itnj4Vd" cx="0" cy="0" r="1" gradientTransform="matrix(2.7406 -7.14959 10.14519 3.88889 10.285 8.99)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="irTaiSd" cx="0" cy="0" r="1" gradientTransform="rotate(-103.052 14.428 -4.084)scale(6.72756 9.54634)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iTUkdGX" cx="0" cy="0" r="1" gradientTransform="rotate(-115.408 11.115 -3.695)scale(2.63838 3.11466)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="iYJMFde" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 16.246 3.722)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iM4psEd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.234 -5.749)scale(6.02662 6.67687)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="iAznjoe" cx="0" cy="0" r="1" gradientTransform="matrix(3.5152 -2.83003 4.38594 5.4478 17.91 6.278)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="itzm0Hd" cx="0" cy="0" r="1" gradientTransform="matrix(2.95886 -2.64821 4.8482 5.41692 18.626 7.536)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="ijxGxsd" cx="0" cy="0" r="1" gradientTransform="matrix(3.22527 .72413 -.30318 1.35036 17.763 5.715)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="iz2Rgde" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.174 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i5C6Wcd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.442 .646)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iUOQtjd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.81 9.998)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iTkvLJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 13.523 10.215)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5Dyhxc" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.61 10.011)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="iu76PLe" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.97 10.556)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iCdkYWc" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 21.084 10.728)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="iqEYJdc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65825 0 0 -1.85168 11.077 10.653)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="ixPB2fd" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.16128 -.93968 11.078 10.656)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><radialGradient id="i5ziYRQ" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.67 8.583)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="ihUuTEe" width="21.944" height="26.818" x="4.962" y="3.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="iWRD0nA" width="12.631" height="14.916" x="9.484" y="8.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/><feGaussianBlur result="effect2_foregroundBlur_4002_3415" stdDeviation=".05"/></filter><filter id="i3Zyh7b" width="5.874" height="5.537" x="6.993" y="23.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".5"/></filter><filter id="igYHWZJ" width="4.98" height="4.054" x="18.51" y="24.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".5"/></filter><filter id="is8Moib" width="2.973" height="2.006" x="21.47" y="23.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="iSo66Bd" width="3.281" height="2" x="20.468" y="25.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="izKJgre" width="13.965" height="11.381" x="9.149" y="12.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.376471 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="it4Y7bv" width="10.996" height="6.432" x="11.932" y="21.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".5"/></filter><filter id="isVaWId" width="2.973" height="2.006" x="7.658" y="23.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="iO6NfJb" width="3.266" height="2" x="8.366" y="25.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="iPZsz3d" width="6.218" height="6.789" x="8.343" y="19.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3415" result="effect2_innerShadow_4002_3415"/></filter><filter id="i0x3x8c" width="6.218" height="6.639" x="17.574" y="19.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3415" result="effect2_innerShadow_4002_3415"/></filter><filter id="iEUlPdc" width="6.702" height="6.417" x="12.683" y="20.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="ilGJtqc" width="6.703" height="6.517" x="12.633" y="20.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".15"/></filter><filter id="iIGKHqd" width="3.2" height="3.2" x="14.271" y="22.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".25"/></filter><filter id="iF1htHe" width="2.35" height="2.35" x="14.893" y="23.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="iU5Sn2b" width="1.458" height="2.505" x="15.848" y="20.577" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".125"/></filter><filter id="isXruLb" width="1.723" height="1.924" x="16.94" y="24.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".125"/></filter><filter id="iqmIIed" width="1.368" height="2.217" x="18.104" y="22.141" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".125"/></filter><filter id="idYKqhb" width="3.55" height="1.942" x="15.171" y="17.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".25"/></filter><filter id="iAu4sLc" width="11.22" height="12.442" x="10.929" y="4.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3415" result="effect2_innerShadow_4002_3415"/></filter><filter id="i7qdxpc" width="3.747" height="4.9" x="13.977" y="9.089" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".5"/></filter><filter id="iw2LW1c" width="2.277" height="3.3" x="14.854" y="9.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".1"/></filter><filter id="igZQYod" width="2.277" height="3.3" x="14.854" y="9.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".1"/></filter><filter id="i9Q47Kc" width="3.718" height="1.573" x="14.133" y="13.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".05"/></filter><filter id="istR5sd" width="12.873" height="8.356" x="9.556" y="1.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3415" result="effect2_innerShadow_4002_3415"/></filter><filter id="iBYnftc" width="2.339" height="1.19" x="17.582" y="7.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="iT8MBtb" width="2.339" height="1.176" x="12.325" y="7.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><filter id="iF5Y36b" width="6.584" height="5.992" x="9.912" y="2.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/><feGaussianBlur result="effect2_foregroundBlur_4002_3415" stdDeviation=".125"/></filter><filter id="iG9JSTc" width="7.112" height="5.986" x="15.833" y="2.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/><feGaussianBlur result="effect2_foregroundBlur_4002_3415" stdDeviation=".125"/></filter><filter id="iOltIpe" width=".787" height=".696" x="17.44" y="9.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".05"/></filter><filter id="iFBVwtd" width=".891" height=".913" x="18.28" y="9.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".1"/></filter><filter id="iRLx7Ib" width=".986" height="1.04" x="13.838" y="9.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".1"/></filter><filter id="i0Lg59c" width=".913" height=".704" x="13.082" y="9.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".05"/></filter><filter id="iVrJOQb" width="1.329" height="2.379" x="9.912" y="9.465" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".125"/></filter><filter id="iMKoq8d" width="1.806" height="2.758" x="20.543" y="9.269" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".25"/></filter><filter id="iQcDuub" width="2.405" height="1.16" x="12.244" y="7.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".125"/></filter><filter id="iULeJ7b" width="2.405" height="1.16" x="17.56" y="7.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".125"/></filter><filter id="i9DJ1fb" width="5.367" height="3.046" x="17.008" y="3.557" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3415" stdDeviation=".375"/></filter><filter id="iJS5A4b" width="15.448" height="4.54" x="8.283" y="2.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3415"/></filter><linearGradient id="islCJXb" x1="26.906" x2="11.7" y1="11.496" y2="21.496" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="ivbEkQN" x1="20.7" x2="10.387" y1="17.402" y2="17.402" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iA1j6ff" x1="14.887" x2="14.887" y1="30.871" y2="29.59" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="iXC7Lmd" x1="23.649" x2="21.867" y1="25.793" y2="24.383" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ivNQXye" x1="22.95" x2="21.169" y1="27.377" y2="25.683" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iIOh4ud" x1="12.653" x2="13.255" y1="29.262" y2="28.918" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="iTyFUGe" x1="7.856" x2="9.361" y1="24.277" y2="26.097" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iJ9tQcQ" x1="9.062" x2="10.843" y1="27.377" y2="25.692" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="i3ONp1q" x1="14.919" x2="16.7" y1="27.141" y2="22.871" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iZUiyFb" x1="13.356" x2="16.981" y1="22.903" y2="23.59" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="imxLKpc" x1="17.231" x2="16.325" y1="26.903" y2="25.153" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iXVKMPb" x1="16.477" x2="16.477" y1="20.824" y2="22.832" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="i343mgd" x1="17.286" x2="18.153" y1="24.879" y2="26.082" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="i6Fz0Td" x1="18.728" x2="18.728" y1="22.411" y2="24.027" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iXqAzDc" x1="16.132" x2="20.117" y1="19.022" y2="17.851" gradientUnits="userSpaceOnUse"><stop class="b63i8aczf"/><stop offset="1" class="v85e7pbqp"/></linearGradient><linearGradient id="iLye4Ke" x1="21.149" x2="18.62" y1="12.599" y2="12.599" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="iTgvy4d" x1="16.831" x2="15.992" y1="11.588" y2="11.623" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="iAmVkvA" x1="15.992" x2="15.992" y1="12.728" y2="12.263" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ib6HYoe" x1="15.992" x2="15.992" y1="9.703" y2="11.295" gradientUnits="userSpaceOnUse"><stop class="hbgmq5b_c"/><stop offset="1" class="u4w6zyb5b"/></linearGradient><linearGradient id="iBtNSvd" x1="14.791" x2="15.109" y1="14.298" y2="13.464" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iMfivjd" x1="22.844" x2="11.232" y1="5.251" y2="5.251" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="iWcGalb" x1="18.952" x2="18.639" y1="10.051" y2="10.245" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLoOf2b" x1="14.554" x2="14.241" y1="10.051" y2="10.244" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ifmElMe" x1="22.429" x2="21.222" y1="10.078" y2="12.254" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="if8mEid" x1="10.143" x2="11.601" y1="10.782" y2="10.655" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iWW02WZ" x1="21.446" x2="21.446" y1="9.769" y2="11.527" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient><linearGradient id="i7ArLZb" x1="20.481" x2="8.544" y1="3.652" y2="7.339" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-veil-medium" /></template>
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

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.acc9bdbvb {
  d: path("M20.854 12.163c.335-.01.649-.124.904-.309v.932c0 .893-.532 1.688-1.34 2.019q.256-.546.345-1.18z");
}

.afbwhdcra {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.762c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.111-.117-.036c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.632c-.044.107-.088.204-.132.31c-.111.293-.303.84-.336 1.135c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b4hfjgbtp {
  d: path("M18.971 10.295a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b59_i1b1o {
  d: path("M27 29.934v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.559 5 23.734 5 28.934v1z");
}

.b63i8aczf {
  stop-color: var(--svg-color--c49987, #C49987);
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.cf6_ffx9f {
  d: path("m11.186 26.303l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.19-.717.059-.797.239c-.3.82-.081 2.136.085 3.001z");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
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

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e_5qze5bt {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.602 9.249c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.232a.23.23 0 0 0 .227-.272A1.4 1.4 0 0 0 13.6 9.25");
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e445prfyo {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m15.61 10.199l-.531 1.838c-.109.378.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.edcynnb_d {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.358a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.ehefnubnv {
  d: path("M11.131 12.163a1.64 1.64 0 0 1-.905-.309v.932c0 .893.532 1.688 1.341 2.019a4.1 4.1 0 0 1-.345-1.18z");
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.er6xh__hd {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("M15.59 10.395L15 12.233c-.1.378.141.756.485.756h.731c.343 0 .585-.384.485-.756l-.495-1.838c-.106-.407-.504-.407-.615 0");
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

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fl44_wb9p {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.59 8.05c-.257-.185-.897-.51-1.655-.382");
}

.ft5dv1b6b {
  fill: none;
}

.fv5c-3h7r {
  d: path("M21.48 25.295c.063-.898.843-1.585 1.721-1.534l.99.059c.121 0 .162.158.149.207c-.176.967-.961 1.703-2 1.633l-.768-.098a.11.11 0 0 1-.102-.117z");
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g5ilm9bus {
  d: path("M15.993 25.226a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.g5ju3nm-w {
  d: path("M18.111 9.71c.064.084-.07.188-.22.3c-.152.114-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.g6q9qacjk {
  fill: var(--svg-color--725050, #725050);
  d: path("M20.391 5.3h-2.137a.496.496 0 1 1 .08-.986c.554.088 1.29.211 1.783.333c1.115.277 1.423.82 1.509 1.206a1.55 1.55 0 0 0-1.235-.552");
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gob_x5bhm {
  d: path("m20.799 26.303l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.19.718.059.798.239c.3.82.081 2.136-.085 3.001z");
}

.gus-gbb9t {
  stop-color: var(--svg-color--824c53, #824C53);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gzbijacst {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M19.725 7.934a1.85 1.85 0 0 0-.687-.412c-.304-.096-.686-.121-1.213-.057a.277.277 0 1 0 .068.55c.48-.058.776-.027.978.036c.199.063.333.164.49.3a.277.277 0 1 0 .364-.417");
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hbgmq5b_c {
  stop-color: var(--svg-color--a5796e, #A5796E);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hlt05jbnl {
  d: path("m21.043 11.527l.094-1.758c.401.054.712.426.712.876c0 .484-.36.878-.806.882");
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.i829wfr2g {
  stop-color: var(--svg-color--8b604a, #8B604A);
  stop-opacity: 0;
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iwey-wb_a {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.41c.096.053.144.218.081.348l-.668 1.39c-.181.388-.526.925-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.324-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.002l-.201.313a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.416l.298-.437a.042.042 0 0 0-.027-.065l-.308-.055a.97.97 0 0 1-.799-1.174a.97.97 0 0 1 1.248-.707l.516.175a.042.042 0 0 0 .055-.042l-.025-.402c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.665.81-1.062v.467c0 .028.028.048.055.039l.458-.156a1 1 0 0 1 .223-.058l.036-.084l1.043.853c.063-.129.19-.198.295-.152c.711.328.494-.417.288.728c-.022.123.015.13.098.03c.74-.9 1.97-1.695 2.682-1.36");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.j9dx1bb5l {
  d: path("M13.808 9.52a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
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

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.jt0rkibcj {
  d: path("m13.196 29.933l-2.547-3.837l5.25-3.475l5.828 2.91l-2.922 4.402z");
}

.jzk7dab5r {
  fill-rule: evenodd;
  d: path("M15.972 4.364c-3.812 0-5.694 1.657-6.334 2.38a.775.775 0 0 1-1.16-1.027c.88-.997 3.165-2.903 7.494-2.903c4.41 0 6.608 1.915 7.54 2.877A.775.775 0 1 1 22.4 6.77c-.735-.758-2.556-2.406-6.428-2.406");
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.kp9ybz5fn {
  d: path("M20.847 4.27c.515.178.976.537 1.268 1.052a2.37 2.37 0 0 1-.106 2.526c-.175.258-.27.564-.27.875V9.91a1.7 1.7 0 0 0-.668-.268l.078-1.607a1.45 1.45 0 0 0-1.378-1.432h-1.4c-.955 0-1.82-.563-2.212-1.443a.66.66 0 0 0-.616-.418h-1.272c-1.846 0-3.342 1.512-3.342 3.379l.03 1.537a1.7 1.7 0 0 0-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.143-2.445a2.34 2.34 0 0 1 1.3-1.127a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.307.51.79.88 1.352 1.073");
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kv4e3-v2a {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.581 7.825a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.067.551a2.22 2.22 0 0 0-1.387.285a1 1 0 0 0-.091.06l-.003.002a.277.277 0 0 1-.34-.439z");
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.kx006679i {
  cx: 13.539px;
  cy: 9.902px;
  rx: 0.39px;
  ry: 0.197px;
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l5m-gut8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.383 9.249c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.371-1.127");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lsfbu9bdl {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.111 9.71c.064.084-.07.188-.22.3c-.152.114-.264.193-.327.108c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mhejshymi {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.027c.324 0 .758.377.758.86v.945");
}

.mhv-kw2uy {
  d: path("M20.914 12.254q.1-1.595.185-3.191a1.61 1.61 0 0 1-.185 3.191");
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n-lindbmp {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 10.413a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o29dz2isc {
  d: path("M23.457 22.762c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.111-.117-.036c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.632c-.044.107-.088.204-.132.31c-.111.293-.303.84-.336 1.135c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
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

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.ov1bd0bys {
  stop-color: var(--svg-color--8b604a, #8B604A);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
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

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q4l6o8wsh {
  d: path("M12.712 23.174c.15-.67.84-1.06 1.5-.85l.62.21a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.56a.05.05 0 0 0 .066.048l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.373-.884 1.493l-.457.101a.05.05 0 0 0-.03.078l.307.423c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.413a.05.05 0 0 0-.081.002l-.242.376c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.527a.05.05 0 0 0-.032-.077l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.qc-g9xhzu {
  d: path("M15.993 13.81c-.508 0-.985-.12-1.386-.328c-.137-.07-.284.084-.198.209c.335.507.919.846 1.583.846c.665 0 1.249-.339 1.584-.846c.086-.13-.061-.28-.198-.21a3 3 0 0 1-1.386.329");
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qqmtywb_k {
  stop-color: var(--svg-color--8b5259, #8B5259);
}

.qvobj7b6r {
  stop-color: var(--svg-color--c2977c, #C2977C);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.r4tpvlruj {
  d: path("M10.52 25.295c-.063-.898-.843-1.585-1.721-1.534l-.99.059c-.121 0-.162.158-.149.207c.176.967.961 1.703 2 1.633l.768-.098a.11.11 0 0 0 .102-.117z");
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rbir1vjpi {
  d: path("m15.61 10.009l-.531 1.838c-.109.378.151.756.52.756h.787c.368 0 .629-.384.52-.756l-.531-1.838c-.114-.408-.646-.408-.765 0");
}

.rboc6roet {
  d: path("M11.167 13.679a3.916 3.916 0 0 0 3.886 3.405h1.887a3.916 3.916 0 0 0 3.885-3.405c.118-1.884.237-3.76.325-5.643a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.616-.418h-1.272c-1.846 0-3.342 1.512-3.342 3.379c0 1.86.116 3.691.238 5.557");
}

.reyqluqkr {
  d: path("m15.61 10.199l-.531 1.838c-.109.378.151.757.52.757h.787c.368 0 .629-.384.52-.757l-.531-1.838c-.114-.407-.646-.407-.765 0");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s6ho2lbhy {
  d: path("M18.176 9.52a.893.893 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.setey9z5u {
  fill: var(--svg-color--000, #000);
  d: path("M17.665 10.413a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
}

.shkcotbtg {
  stop-color: var(--svg-color--a97b73, #A97B73);
}

.sjnpwht8s {
  d: path("M14.624 10.308c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.u4w6zyb5b {
  stop-color: var(--svg-color--a5796e, #A5796E);
  stop-opacity: 0;
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
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

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.uubrgfq8x {
  stop-color: var(--svg-color--8b5c5a, #8B5C5A);
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

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.v85e7pbqp {
  stop-color: var(--svg-color--c49987, #C49987);
  stop-opacity: 0;
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vcabx4bgj {
  d: path("m21.205 8.565l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vl91zwoht {
  cx: 9.168px;
  cy: 20.5px;
  r: 0.762px;
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vtlqp6_0b {
  d: path("M9.15 20.466a11.2 11.2 0 0 1 4.31-2.047c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.519");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.w-m7nbbyp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.847c.395.01 1.357-.063 2.05-.442");
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
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

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.x009kdzqb {
  d: path("M10.907 9.715a.956.956 0 0 0 .083 1.88a78 78 0 0 1-.083-1.88");
}

.x15soc1he {
  stop-color: var(--svg-color--966c60, #966C60);
  stop-opacity: 0;
}

.x315_wofb {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.642 13.415a.23.23 0 0 0-.272.047a.21.21 0 0 0-.023.27c.348.528.955.88 1.646.88c.69 0 1.297-.352 1.645-.88a.214.214 0 0 0-.023-.273a.23.23 0 0 0-.271-.044c-.39.203-.85.32-1.352.32a2.9 2.9 0 0 1-1.35-.32Z");
}

.x5158qbnu {
  stop-color: var(--svg-color--a97b73, #A97B73);
  stop-opacity: 0;
}

.x8hqoxpur {
  stroke: var(--svg-color--553f3f, #553F3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.62 8.105c.256-.185.897-.51 1.654-.382");
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xne16_jnl {
  fill: var(--svg-color--563936, #563936);
  d: path("m21.205 8.565l-.03-.631c-.01-.764-.64-1.394-1.405-1.426h-1.4a2.42 2.42 0 0 1-2.124-1.26s-.058-.135-.12-.368c-.256-.97.671-1.712 1.656-1.521c.974.189 2.082.517 2.902 1.052c1.745 1.137 1.44 3.188.521 4.154");
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xs57zoclf {
  d: path("M10.948 9.05a1.62 1.62 0 0 0-1.392 1.598c0 .86.673 1.561 1.52 1.607a78 78 0 0 1-.128-3.205");
}

.xvtzdvb_i {
  fill: var(--svg-color--533634, #533634);
  d: path("m16.225 5.298l-.066-.137a.66.66 0 0 0-.616-.418h-1.272c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.332-.253l.1-.105c.349-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.893v1.485z");
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xy2hs8s1u {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.762c-.076-.156-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.634c.099.12.144.111.117-.036c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.632l.133.31c.111.293.303.84.336 1.135c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.y_-nyz7qb {
  d: path("M11.39 25.809c-.678-.6-1.716-.536-2.298.112l-.69.734c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.y1diaublm {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.793l.907 1.18");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.ysbaxhbyq {
  stop-color: var(--svg-color--966c60, #966C60);
}

.ytgsxobsm {
  d: path("m16.225 5.298l-.066-.137a.66.66 0 0 0-.616-.418h-1.272c-1.846 0-3.342 1.512-3.342 3.379v.275c-.34-.259-.768-.804-.768-1.688c0-1.072.782-1.613 1.28-1.959c.142-.097.26-.18.332-.253l.1-.105c.349-.37.972-1.031 2.06-1.32a5.5 5.5 0 0 1 1.507-.165c.473.011.806.42.806.893v1.485z");
}

.yvs0b-mya {
  cx: 13.539px;
  cy: 9.902px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zbtz915uf {
  stop-color: var(--svg-color--99616e, #99616E);
  stop-opacity: 0;
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zrr9gv88m {
  stop-color: var(--svg-color--9e755f, #9E755F);
}

.zsj5_9a3c {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.974c.78-.46 1.787-.2 2.235.546l.538.851c.048.079.043.217-.074.262c-1 .38-2.053.104-2.561-.77l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
