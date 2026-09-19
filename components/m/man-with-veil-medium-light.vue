<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ilNpyme)"><path fill="url(#iFXlEqd)" class="ji8yh5bla"/><path fill="url(#i24RWIe)" class="ji8yh5bla"/><path fill="url(#idGj1be)" class="ji8yh5bla"/></g><g filter="url(#iWwwrLd)"><path fill="url(#i0SD3Mg)" class="kvwr9yboz"/></g><path fill="url(#i8tgQMb)" class="r539zcikc"/><path fill="url(#iOT6XLb)" class="r539zcikc"/><path fill="url(#id69vYc)" class="r539zcikc"/><path fill="url(#ifvxyQb)" class="r539zcikc"/><g filter="url(#iCnPEUc)"><path class="aalucbc0g"/></g><g filter="url(#iX9WSKc)"><path class="odrnedbud"/></g><g filter="url(#i2xjbbb)"><path fill="url(#iySRo4c)" class="aohb1hb9e"/><path fill="url(#i3OnOsd)" class="aohb1hb9e"/><path fill="url(#igupTOe)" class="aohb1hb9e"/></g><g filter="url(#ikylgFe)"><path fill="url(#ifSgfQb)" class="od51fm6nq"/><path fill="url(#iuQrLPc)" class="od51fm6nq"/><path fill="url(#idQLy5d)" class="od51fm6nq"/></g><g filter="url(#i1v4hPb)"><path fill="url(#iJRBxZc)" class="zfsukvjyp"/><path fill="url(#i8SSRui)" class="zfsukvjyp"/><path fill="url(#imq3L8c)" class="zfsukvjyp"/><path fill="url(#i8r4Nfz)" class="zfsukvjyp"/><path fill="url(#iisXXib)" class="zfsukvjyp"/></g><path fill="url(#iowjiNc)" class="xwongh8se"/><path fill="url(#iLcqwYb)" class="xwongh8se"/><g filter="url(#iHiNgyb)"><path class="styk74bai"/></g><g filter="url(#i06490F)"><path fill="url(#itgnD4b)" class="gc3benb6z"/><path fill="url(#iZ01QJY)" class="gc3benb6z"/></g><g filter="url(#i8D2LMd)"><path fill="url(#iu8Jx2d)" class="e0277cy0d"/><path fill="url(#iyvZLGd)" class="e0277cy0d"/></g><circle fill="url(#ilXtz2b)" class="wwlpcwbvn"/><circle fill="url(#iXxSc8U)" class="wwlpcwbvn"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.392)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.392)" class="movji7bnz"/><circle fill="url(#iAhzi9c)" class="d47rbobje"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.45)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.45)" class="movji7bnz"/><path fill="url(#ioyOuhc)" class="fa6r-pbzp"/><g filter="url(#is1apNc)"><path class="l97-mebsg"/><path fill="url(#iBSwZls)" class="dxjhxebrx"/><path fill="url(#ivPkKLd)" class="dxjhxebrx"/><path fill="url(#ibBFqnb)" class="dxjhxebrx"/><path fill="url(#ivj5E2c)" class="dxjhxebrx"/><path fill="url(#ibKhCQe)" class="dxjhxebrx"/></g><path fill="url(#iqGMOJL)" class="hnvjxbbrk"/><g filter="url(#i3nXBlz)"><path class="msl-cu1ur"/><path fill="url(#i0O715b)" class="g3mu-1f7d"/><path fill="url(#i2HTMEJ)" class="g3mu-1f7d"/></g><g filter="url(#iRJ9DEb)"><path class="oqg71cmnn"/><path fill="url(#i9q2Ncb)" class="c0-eeousz"/><path fill="url(#irewSxy)" class="c0-eeousz"/><path fill="url(#ixIGdSw)" class="c0-eeousz"/><path fill="url(#iaPApAP)" class="c0-eeousz"/><path fill="url(#iOnrVYb)" class="c0-eeousz"/></g><g filter="url(#iXukOcb)"><path fill="url(#iRJT5ke)" clip-rule="evenodd" class="g8n8t9nrj"/></g><g filter="url(#iJqE1gd)"><path class="e-ehdobhs"/></g><g filter="url(#irsOf5J)"><path fill="url(#iEssCNd)" class="vvgm3n0fn"/><path fill="url(#izjYfzP)" class="vvgm3n0fn"/></g><g filter="url(#ipaZZCd)"><path stroke="url(#iL4CYEd)" class="iz-34drmi"/></g><g filter="url(#isEHXOe)"><path stroke="url(#iw6ybGb)" class="pcszcjyvy"/></g><g filter="url(#i95tQge)"><path stroke="url(#iR0VNHY)" class="v-0xo4miq"/></g><g filter="url(#iB3UeHb)"><path stroke="url(#ieeYr2I)" class="q4e11dbxm"/></g><g filter="url(#i6jfeYb)"><circle fill="url(#ioAgOON)" class="e_fan6h1u"/></g><g filter="url(#iku2Qpc)"><circle fill="url(#ieRyBGe)" class="t9m304bnt"/></g><g filter="url(#ir9xbTd)"><circle fill="url(#iQylxye)" class="l526kmf0e"/><circle fill="url(#iw9TRQd)" class="l526kmf0e"/></g><g filter="url(#iBZLWkq)"><circle class="aob6sabbx"/><circle fill="url(#iSR7dlP)" class="ykmxyzbge"/><circle fill="url(#ibh7wVO)" class="ykmxyzbge"/></g><g filter="url(#iP3hcYc)"><path fill="url(#iFri6xd)" class="z3dw9fbjd"/><path fill="url(#iNdPnvd)" class="z3dw9fbjd"/><path fill="url(#iZNKMZc)" class="z3dw9fbjd"/><path fill="url(#ipygi5d)" class="z3dw9fbjd"/><path fill="url(#i9laiDd)" class="z3dw9fbjd"/></g><g filter="url(#iOgSFke)"><path class="z9oy-1b3u"/><path fill="url(#ip225uc)" class="yykf3-jou"/><path fill="url(#igKMZOe)" class="yykf3-jou"/><path fill="url(#i3qJ5Bb)" class="yykf3-jou"/><path fill="url(#iQkiPZd)" class="yykf3-jou"/><path fill="url(#i2JiUve)" class="yykf3-jou"/></g><path fill="url(#iPNEBbe)" class="yykf3-jou"/><path fill="url(#iG1Xlrd)" class="yykf3-jou"/><g filter="url(#iJkiw8b)"><path class="pn--edb8i"/></g><g filter="url(#i2Yhk6d)"><path class="ssouifb0x"/><path fill="url(#iPk2Gqd)" class="esynb_wqe"/><path fill="url(#iiwfLKd)" class="esynb_wqe"/><path fill="url(#iDVgxph)" class="esynb_wqe"/></g><path stroke="url(#iMKZD2b)" class="clghz59-f"/><g filter="url(#iE3y96d)"><path class="k_ng-b63x"/></g><g filter="url(#iwTzjAd)"><path class="x4-l745no"/></g><path class="ih3hp3j7c"/><path fill="url(#ismBeVd)" class="dbg75g3ir"/><path class="en0s20m1x"/><g filter="url(#iih3S6b)"><path class="d9ku5ybae"/><path fill="url(#i7zK1Ke)" class="hw7ecvb7x"/></g><g filter="url(#iyoZRcx)"><path fill="url(#iOGtU2d)" class="j5sj9ab8y"/></g><path class="aabjj8b9i"/><path fill="url(#i39MIRG)" class="llzxqbc5g"/><path class="k3ovads3w"/><g filter="url(#iClhHFZ)"><path fill="url(#i4wpzQb)" class="q75kkv80f"/></g><g filter="url(#io3Ro7V)"><ellipse transform="rotate(-27.914 13.515 9.897)" class="zhmwxyqur"/><ellipse fill="url(#iWW2Iic)" transform="rotate(-27.914 13.515 9.897)" class="ysr1zshys"/></g><g filter="url(#iHGKCtb)"><path stroke="url(#iz8HCJc)" class="bxmncqlds"/></g><g filter="url(#iPLvDps)"><path stroke="url(#i6nrFTX)" class="hxj7jlf7h"/></g><g filter="url(#iG4kCne)"><path fill="url(#iMw1ACb)" clip-rule="evenodd" class="lc3gnebtx"/><path fill="url(#ijfvaQd)" clip-rule="evenodd" class="lc3gnebtx"/></g><defs><radialGradient id="i24RWIe" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.829 7.012)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="idGj1be" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.614)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="i8tgQMb" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.154 15.724)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="id69vYc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.989)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="ifvxyQb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.145)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="i3OnOsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.783)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="igupTOe" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.64 14.62)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iuQrLPc" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.763 27.286)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="idQLy5d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.848)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iJRBxZc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.95206 -2.46677 3.46444 -9.76378 21.531 21.567)" gradientUnits="userSpaceOnUse"><stop class="rytnnmv8a"/><stop offset="1" class="b3fwc4m_l"/></radialGradient><radialGradient id="i8SSRui" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.73 16.614)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="v0p7hcb9x"/><stop offset="1" class="licq-dbtd"/></radialGradient><radialGradient id="imq3L8c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.10937 .98438 -.41833 -1.3214 16.117 16.64)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="fotkl_b9q"/><stop offset="1" class="ia04nc2ae"/></radialGradient><radialGradient id="i8r4Nfz" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07223 -.6455 .5202 -.8641 22.585 20.79)" gradientUnits="userSpaceOnUse"><stop class="qe7efdbrr"/><stop offset="1" class="ox8o7cb9c"/></radialGradient><radialGradient id="iisXXib" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.67275 0 14.336 16.682)" gradientUnits="userSpaceOnUse"><stop class="ko0wcdkuo"/><stop offset="1" class="qqn01fflj"/></radialGradient><radialGradient id="iowjiNc" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.702 35.876)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="iZ01QJY" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.155 4.902)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iyvZLGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.285)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="ilXtz2b" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.318 11.791)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="iXxSc8U" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.418 14.586)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="iAhzi9c" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.355 12.647)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="ioyOuhc" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.353 19.357)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="iBSwZls" cx="0" cy="0" r="1" gradientTransform="matrix(1.56458 3.75 -.74545 .31102 12.95 20.99)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="ivPkKLd" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.481 22.989)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="ibBFqnb" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.168 9.213)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="ivj5E2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.28 24.784)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="ibKhCQe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.567)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="iqGMOJL" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.786)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="i0O715b" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.692)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="i2HTMEJ" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.706)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="i9q2Ncb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.27)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="irewSxy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.958)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iRJT5ke" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.314 16.625)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iEssCNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.386 23.834)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="izjYfzP" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.219)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="ioAgOON" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07076 9.554 10.675)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iw9TRQd" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.107 10.41)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iSR7dlP" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.694 11.495)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="ibh7wVO" cx="0" cy="0" r="1" gradientTransform="matrix(.25926 .25663 -.33084 .33423 20.736 10.674)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iNdPnvd" cx="0" cy="0" r="1" gradientTransform="scale(9.60897 10.0575)rotate(90 .49 1.22)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="uzp26-bok"/><stop offset="1" class="hqdkok6mw"/></radialGradient><radialGradient id="ipygi5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60857 0 18.316 9.403)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="i9laiDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.759 9.37)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="ip225uc" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.106 6.296)scale(5.6057 9.53299)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="i3qJ5Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06682 -1.86131 .91413 -.03282 11.778 7.219)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="iQkiPZd" cx="0" cy="0" r="1" gradientTransform="matrix(.85907 -1.96631 1.60368 .70064 20.197 8.937)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="i2JiUve" cx="0" cy="0" r="1" gradientTransform="matrix(.9927 1.23176 -1.08755 .87648 15.195 2.074)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="iPNEBbe" cx="0" cy="0" r="1" gradientTransform="matrix(.18136 .78313 -1.28748 .29815 16.665 2.074)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="iG1Xlrd" cx="0" cy="0" r="1" gradientTransform="matrix(.72544 .89725 -2.0104 1.62544 11.625 3.802)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="ismBeVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90308 -1.06858 0 18.15 10.325)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i7zK1Ke" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.428 .65)scale(.37817 .52064)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i39MIRG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90312 -1.06863 0 13.786 10.326)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iWW2Iic" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.777 -1.54)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijfvaQd" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.672 8.58)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="ilNpyme" width="21.944" height="26.818" x="4.962" y="3.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="iWwwrLd" width="12.631" height="14.916" x="9.484" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/><feGaussianBlur result="effect2_foregroundBlur_4002_3420" stdDeviation=".05"/></filter><filter id="iCnPEUc" width="5.874" height="5.537" x="6.993" y="23.135" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".5"/></filter><filter id="iX9WSKc" width="4.98" height="4.054" x="18.51" y="24.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".5"/></filter><filter id="i2xjbbb" width="2.973" height="2.006" x="21.47" y="23.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="ikylgFe" width="3.281" height="2" x="20.468" y="25.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="i1v4hPb" width="13.965" height="11.381" x="9.149" y="12.596" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.560784 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="iHiNgyb" width="10.996" height="6.432" x="11.932" y="21.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".5"/></filter><filter id="i06490F" width="2.973" height="2.006" x="7.658" y="23.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="i8D2LMd" width="3.266" height="2" x="8.366" y="25.288" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="is1apNc" width="6.218" height="6.789" x="8.343" y="19.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3420" result="effect2_innerShadow_4002_3420"/></filter><filter id="i3nXBlz" width="6.218" height="6.639" x="17.574" y="19.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3420" result="effect2_innerShadow_4002_3420"/></filter><filter id="iRJ9DEb" width="6.702" height="6.417" x="12.683" y="20.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="iXukOcb" width="6.703" height="6.517" x="12.633" y="20.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".15"/></filter><filter id="iJqE1gd" width="3.2" height="3.2" x="14.271" y="22.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".25"/></filter><filter id="irsOf5J" width="2.35" height="2.35" x="14.893" y="23.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="ipaZZCd" width="1.458" height="2.505" x="15.848" y="20.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".125"/></filter><filter id="isEHXOe" width="1.724" height="1.924" x="16.94" y="24.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".125"/></filter><filter id="i95tQge" width="1.368" height="2.217" x="18.104" y="22.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".125"/></filter><filter id="iB3UeHb" width="3.55" height="1.942" x="15.171" y="17.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".25"/></filter><filter id="i6jfeYb" width="3.539" height="3.339" x="9.554" y="9.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="iku2Qpc" width="2.99" height="2.99" x="9.728" y="9.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".25"/></filter><filter id="ir9xbTd" width="3.589" height="3.589" x="19.066" y="8.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="iBZLWkq" width="2.99" height="2.99" x="19.241" y="9.179" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".25"/></filter><filter id="iP3hcYc" width="10.373" height="12.177" x="10.813" y="5.05" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="iOgSFke" width="12.601" height="8.543" x="9.67" y="1.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="iJkiw8b" width="3.26" height="4.181" x="14.102" y="9.52" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".375"/></filter><filter id="i2Yhk6d" width="2.377" height="3.181" x="14.782" y="9.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".125"/></filter><filter id="iE3y96d" width="2.979" height="1.873" x="17.152" y="7.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="iwTzjAd" width="2.98" height="1.873" x="12.005" y="7.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><filter id="iih3S6b" width=".787" height=".696" x="17.415" y="9.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".05"/></filter><filter id="iyoZRcx" width=".891" height=".913" x="18.255" y="9.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".1"/></filter><filter id="iClhHFZ" width=".986" height="1.04" x="13.813" y="9.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".1"/></filter><filter id="io3Ro7V" width=".913" height=".704" x="13.059" y="9.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".05"/></filter><filter id="iHGKCtb" width="3.099" height="1.681" x="17.006" y="7.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".25"/></filter><filter id="iPLvDps" width="3.177" height="1.738" x="11.787" y="7.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3420" stdDeviation=".25"/></filter><filter id="iG4kCne" width="15.448" height="4.54" x="8.283" y="2.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3420"/></filter><linearGradient id="iFXlEqd" x1="26.906" x2="11.7" y1="11.489" y2="21.489" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="i0SD3Mg" x1="20.7" x2="10.387" y1="17.395" y2="17.395" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iOT6XLb" x1="14.887" x2="14.887" y1="30.864" y2="29.583" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="iySRo4c" x1="23.649" x2="21.867" y1="25.786" y2="24.375" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ifSgfQb" x1="22.95" x2="21.169" y1="27.37" y2="25.676" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iLcqwYb" x1="12.653" x2="13.255" y1="29.254" y2="28.911" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="itgnD4b" x1="7.856" x2="9.361" y1="24.27" y2="26.09" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iu8Jx2d" x1="9.062" x2="10.843" y1="27.369" y2="25.684" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="ixIGdSw" x1="14.919" x2="16.7" y1="27.133" y2="22.864" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iaPApAP" x1="13.356" x2="16.981" y1="22.895" y2="23.583" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iOnrVYb" x1="17.231" x2="16.325" y1="26.895" y2="25.145" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iL4CYEd" x1="16.477" x2="16.477" y1="20.817" y2="22.825" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iw6ybGb" x1="17.286" x2="18.153" y1="24.872" y2="26.075" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iR0VNHY" x1="18.728" x2="18.728" y1="22.403" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="ieeYr2I" x1="16.132" x2="20.117" y1="19.015" y2="17.843" gradientUnits="userSpaceOnUse"><stop class="cylb5xhsz"/><stop offset="1" class="zcstuupfv"/></linearGradient><linearGradient id="ieRyBGe" x1="11.223" x2="10.582" y1="10.953" y2="10.953" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="iQylxye" x1="21.822" x2="21.003" y1="9.583" y2="12.119" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="iFri6xd" x1="20.006" x2="12.37" y1="11.064" y2="12.202" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="iZNKMZc" x1="10.575" x2="12.887" y1="13.759" y2="13.458" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="igKMZOe" x1="11.11" x2="14.012" y1="10.407" y2="5.253" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iPk2Gqd" x1="15.106" x2="16.044" y1="11.723" y2="11.723" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="iiwfLKd" x1="16.909" x2="15.883" y1="12.046" y2="12.031" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iDVgxph" x1="16.165" x2="16.165" y1="12.788" y2="12.215" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="iMKZD2b" x1="14.934" x2="15.368" y1="14.402" y2="13.715" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="iOGtU2d" x1="18.927" x2="18.613" y1="10.046" y2="10.239" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i4wpzQb" x1="14.53" x2="14.216" y1="10.046" y2="10.239" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iz8HCJc" x1="18.942" x2="18.522" y1="7.907" y2="7.048" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="i6nrFTX" x1="13.638" x2="12.449" y1="7.779" y2="7.28" gradientUnits="userSpaceOnUse"><stop class="pqf0u3bgb"/><stop offset="1" class="xogpiobqs"/></linearGradient><linearGradient id="iMw1ACb" x1="20.481" x2="8.544" y1="3.645" y2="7.332" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-veil-medium-light" /></template>
<style>
.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.aabjj8b9i {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.578 9.244c-.653 0-1.205.45-1.355 1.058c-.045.175.09.34.268.34h2.23a.23.23 0 0 0 .227-.27a1.4 1.4 0 0 0-1.37-1.128");
}

.aalucbc0g {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.138c.879-.051 1.658.636 1.72 1.534l.009.116c.31.044.61.175.862.397l.107.114a.11.11 0 0 1 .01.15l-.42.582c-.665.763-1.75.834-2.66.271c-.064-.05-.086-.203-.024-.27l.69-.735q.136-.151.302-.26c-.906-.06-1.574-.75-1.735-1.633c-.013-.05.028-.207.15-.207z");
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.aob6sabbx {
  cx: 20.735px;
  cy: 10.674px;
  r: 0.995px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.aohb1hb9e {
  d: path("M21.48 25.288c.063-.898.843-1.585 1.721-1.534l.99.059c.121 0 .162.158.149.207c-.176.966-.961 1.703-2 1.633l-.768-.098a.11.11 0 0 1-.102-.117z");
}

.b3fwc4m_l {
  stop-color: var(--svg-color--da9f7c, #DA9F7C);
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.bxmncqlds {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.63 7.81c.43-.075 1.27-.054 1.85.398");
}

.c0-eeousz {
  d: path("M12.712 23.166c.15-.67.84-1.06 1.5-.85l.62.212a.05.05 0 0 0 .066-.051l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.562a.05.05 0 0 0 .066.047l.55-.187c.64-.24 1.31.058 1.49.728c.17.65-.214 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.08l.307.422c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clghz59-f {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.609 13.43a2.94 2.94 0 0 0 1.361.324c.505 0 .969-.118 1.362-.323a.2.2 0 0 1 .242.04a.19.19 0 0 1 .02.24m-2.986-.28l2.945.253m-2.945-.253a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.253m3.207.028l-.042-.028m.042.028l-.042-.028m.042.028a1.94 1.94 0 0 1-1.625.868c-.681 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.583-.846m-.04.028l.04-.028m-.04.028h-.001l.041-.028");
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cylb5xhsz {
  stop-color: var(--svg-color--f6bea1, #F6BEA1);
}

.d47rbobje {
  cx: 10.18px;
  cy: 21.571px;
  r: 0.762px;
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.d9ku5ybae {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.086 9.704c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.dbg75g3ir {
  d: path("M18.151 9.515a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dxjhxebrx {
  d: path("M8.528 22.754c-.076-.155-.018-.354.098-.418c.854-.403 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.028.355.183l.753 1.631l.133.311c.111.293.303.84.336 1.135c.152 1.231-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.361c-.34-.302-.754-.948-.972-1.414z");
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e_fan6h1u {
  cx: 11.223px;
  cy: 10.675px;
  r: 1.669px;
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e-ehdobhs {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.35a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.e0277cy0d {
  d: path("M11.39 25.801c-.678-.599-1.716-.535-2.298.112l-.69.735c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
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

.en0s20m1x {
  fill: var(--svg-color--000, #000);
  d: path("M17.64 10.408c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.235");
}

.esynb_wqe {
  d: path("m15.588 10.39l-.531 1.699a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .521-.7l-.531-1.699c-.114-.376-.646-.376-.765 0");
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.fa6r-pbzp {
  d: path("m11.186 26.296l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.19-.717.058-.797.238c-.3.82-.081 2.137.085 3.002z");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fotkl_b9q {
  stop-color: var(--svg-color--c87c6c, #C87C6C);
}

.ft5dv1b6b {
  fill: none;
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g3mu-1f7d {
  d: path("M23.457 22.754c.076-.155.018-.354-.098-.418c-.854-.403-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.84-.336 1.135c-.152 1.231.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.361c.34-.302.754-.948.972-1.414z");
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.g8n8t9nrj {
  fill-rule: evenodd;
  d: path("M13.709 24.33a.913.913 0 0 1-.753-1.108a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.302l-.03-.485v-.006q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.56a.3.3 0 0 0 .396.285l.551-.188l.007-.002c.516-.194 1.023.046 1.16.558c.14.533-.183 1.094-.687 1.184l-.466.103a.3.3 0 0 0-.178.469l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.3-1.012.16-1.32-.295L16.18 26a.3.3 0 0 0-.493.017l-.247.383l-.005.008a.91.91 0 0 1-1.294.33l-.001-.001a.92.92 0 0 1-.227-1.336l.005-.006l.362-.533a.3.3 0 0 0-.196-.464l-.369-.067z");
}

.gc3benb6z {
  d: path("M10.52 25.288c-.063-.898-.843-1.585-1.721-1.534l-.99.059c-.121 0-.162.158-.149.207c.176.966.961 1.703 2 1.633l.768-.098a.11.11 0 0 0 .102-.117z");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hnvjxbbrk {
  d: path("m20.799 26.296l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.19.718.058.798.238c.3.82.081 2.137-.085 3.002z");
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hqdkok6mw {
  stop-color: var(--svg-color--bf766d, #BF766D);
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.hw7ecvb7x {
  d: path("M18.086 9.704c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.389-.05");
}

.hxj7jlf7h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.412 8.329c.327-.29 1.041-.594 1.927-.453");
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.ia04nc2ae {
  stop-color: var(--svg-color--c87c6c, #C87C6C);
  stop-opacity: 0;
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.ih3hp3j7c {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.358 9.244c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.271c.126-.64.69-1.127 1.371-1.127");
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.iz-34drmi {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.02c.324 0 .758.376.758.86v.945");
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j5sj9ab8y {
  d: path("M18.946 10.29a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.ji8yh5bla {
  d: path("M5.062 16.426c0-8.812 4.89-13.218 10.922-13.218s10.922 4.218 10.922 13.218v13.5H5.062z");
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k_ng-b63x {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M19.69 7.954h-.002l-.002-.002l-.004-.004l-.012-.01a2 2 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.16a.534.534 0 1 0 .166 1.055c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .679-.824");
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.k3ovads3w {
  fill: var(--svg-color--000, #000);
  d: path("M14.295 10.408a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.235");
}

.ko0wcdkuo {
  stop-color: var(--svg-color--db977c, #DB977C);
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.kvwr9yboz {
  d: path("M9.984 15.849c0-4.854 2.694-7.281 6.016-7.281s6.016 2.324 6.016 7.28v7.436H9.984z");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l526kmf0e {
  cx: 20.735px;
  cy: 10.675px;
  r: 1.669px;
}

.l97-mebsg {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.754c-.076-.155-.018-.354.098-.418c.854-.403 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.028.355.183l.753 1.631l.133.311c.111.293.303.84.336 1.135c.152 1.231-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.361c-.34-.302-.754-.948-.972-1.414z");
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.lc3gnebtx {
  fill-rule: evenodd;
  d: path("M15.972 4.357c-3.812 0-5.694 1.657-6.334 2.38a.775.775 0 1 1-1.16-1.028c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.915 7.54 2.876a.775.775 0 1 1-1.112 1.08c-.735-.758-2.556-2.406-6.428-2.406");
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.licq-dbtd {
  stop-color: var(--svg-color--d6927c, #D6927C);
  stop-opacity: 0;
}

.llzxqbc5g {
  d: path("M13.784 9.515a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.236a.9.9 0 0 0-.897-.892");
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.msl-cu1ur {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.754c.076-.155.018-.354-.098-.418c-.854-.403-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.84-.336 1.135c-.152 1.231.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.361c.34-.302.754-.948.972-1.414z");
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

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
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

.od51fm6nq {
  d: path("M20.61 25.801c.678-.599 1.716-.535 2.297.112l.69.735c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.odrnedbud {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.967c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.043.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.651a.11.11 0 0 1 .037-.146z");
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.oqg71cmnn {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.166c.15-.67.84-1.06 1.5-.85l.62.212a.05.05 0 0 0 .066-.051l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.562a.05.05 0 0 0 .066.047l.55-.187c.64-.24 1.31.058 1.49.728c.17.65-.214 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.08l.307.422c.44.52.34 1.32-.22 1.71s-1.296.192-1.67-.36l-.31-.414a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.ox8o7cb9c {
  stop-color: var(--svg-color--db9f70, #DB9F70);
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

.pcszcjyvy {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.786l.907 1.18");
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn--edb8i {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.695 10.552l-.82 1.7c-.102.35.142.699.488.699h.737c.346 0 .59-.355.488-.7l-.498-1.699c-.107-.376-.283-.376-.395 0");
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.pqf0u3bgb {
  stop-color: var(--svg-color--a57146, #A57146);
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q4e11dbxm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.84c.395.01 1.357-.064 2.05-.442");
}

.q75kkv80f {
  d: path("M14.6 10.303c0-.289-.235-.48-.298-.539l-.289.279l.178.361z");
}

.qe7efdbrr {
  stop-color: var(--svg-color--db9f70, #DB9F70);
}

.qqn01fflj {
  stop-color: var(--svg-color--db977c, #DB977C);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.r539zcikc {
  d: path("M27 29.927v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.552 5 23.727 5 28.927v1z");
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.rytnnmv8a {
  stop-color: var(--svg-color--f6bf99, #F6BF99);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.ssouifb0x {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.588 10.39l-.531 1.699a.54.54 0 0 0 .52.699h.786a.54.54 0 0 0 .521-.7l-.531-1.699c-.114-.376-.646-.376-.765 0");
}

.styk74bai {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.402c.096.054.144.22.081.348l-.668 1.39c-.181.389-.526.926-.809 1.178c-.687.638-1.466.645-2.21.3a2.4 2.4 0 0 1-.481-.292a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.343a.042.042 0 0 0-.068.002l-.201.313a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.416l.298-.438a.042.042 0 0 0-.027-.064l-.308-.055a.97.97 0 0 1-.799-1.174a.97.97 0 0 1 1.248-.707l.516.175a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.557.514 1.048 1.08 1.04c.574-.008.81-1.664.81-1.062v.467c0 .029.028.049.055.04l.458-.156q.112-.042.223-.058l.036-.085l1.043.854c.063-.13.19-.198.295-.152c.711.327.494-.417.288.728c-.022.123.015.13.098.03c.74-.9 1.97-1.696 2.682-1.36");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t9m304bnt {
  cx: 11.223px;
  cy: 10.674px;
  r: 0.995px;
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
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

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.uzp26-bok {
  stop-color: var(--svg-color--ce9185, #CE9185);
  stop-opacity: 0;
}

.v-0xo4miq {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.567c.307.135.83.616.461 1.453");
}

.v0p7hcb9x {
  stop-color: var(--svg-color--d6927c, #D6927C);
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vvgm3n0fn {
  d: path("M15.993 25.219a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.wwlpcwbvn {
  cx: 9.168px;
  cy: 20.493px;
  r: 0.762px;
}

.x4-l745no {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M12.197 7.954h.002l.002-.002l.004-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.16a.534.534 0 0 1-.166 1.055a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.824");
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xogpiobqs {
  stop-color: var(--svg-color--a57146, #A57146);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.xwongh8se {
  d: path("m13.196 29.926l-2.547-3.837l5.25-3.475l5.828 2.909l-2.922 4.403z");
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.ykmxyzbge {
  cx: 20.735px;
  cy: 10.674px;
  r: 0.995px;
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.ysr1zshys {
  cx: 13.515px;
  cy: 9.897px;
  rx: 0.389px;
  ry: 0.197px;
}

.yykf3-jou {
  d: path("m20.789 4.197l.429.213c.75.374 1.18 1.227 1.019 2.134l-.59 3.04c-.053.313-.26.524-.572.532h-.018s.054-.906.107-1.44c.044-.432-.032-.564-.429-.96c-.214-.213-.375-.533-.375-.853V6.01c0-.266-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.429.533v.853c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.049-.001a.63.63 0 0 1-.594-.532l-.59-3.04c-.108-.853.321-1.706 1.072-2.08l.43-.213c.267-.16.536-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.266 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.z3dw9fbjd {
  d: path("m10.871 10.062l.05.001s-.054-.853-.108-1.44c0-.266.107-.586.322-.746l.16-.16c.269-.214.376-.534.376-.854V6.01c0-.266.16-.48.43-.533c.643-.16 1.984-.427 3.914-.427s3.272.267 3.916.427c.214.053.429.267.429.533v.853c0 .32.16.64.375.854c.502.352.471.545.43.96c-.054.533-.108 1.44-.108 1.44h.018l-.266 3.957c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003z");
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.z9oy-1b3u {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m20.789 4.197l.429.213c.75.374 1.18 1.227 1.019 2.134l-.59 3.04c-.053.313-.26.524-.572.532h-.018s.054-.906.107-1.44c.044-.432-.032-.564-.429-.96c-.214-.213-.375-.533-.375-.853V6.01c0-.266-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.429.533v.853c0 .32-.107.64-.375.854l-.161.16c-.215.16-.322.48-.322.746c.053.587.107 1.44.107 1.44l-.049-.001a.63.63 0 0 1-.594-.532l-.59-3.04c-.108-.853.321-1.706 1.072-2.08l.43-.213c.267-.16.536-.373.804-.587l.965-1.013c.59-.533 1.448-.693 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.266 1.716-.053 2.36.533l.804.8c.215.267.483.427.805.587");
}

.zcstuupfv {
  stop-color: var(--svg-color--f6bea1, #F6BEA1);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zfsukvjyp {
  d: path("M9.15 20.459a11.2 11.2 0 0 1 4.31-2.047c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.062a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zhmwxyqur {
  cx: 13.515px;
  cy: 9.897px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
