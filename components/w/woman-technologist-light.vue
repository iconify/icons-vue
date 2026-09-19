<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ix0aLxe)" class="nzepf2bjg"/><path fill="url(#iFopWnc)" class="kps7ecbkn"/><path fill="url(#iO45OWc)" class="a1q-0ubvc"/><path fill="url(#iuQTVIb)" class="a1q-0ubvc"/><path fill="url(#iFw5Zzd)" class="a1q-0ubvc"/><path class="cy4dfghcf"/><path fill="url(#iquoPDd)" class="pt1lol2at"/><path fill="url(#iaYeuCc)" class="pt1lol2at"/><path fill="url(#iYHxild)" class="sddnkbbus"/><path fill="url(#ixi72Gc)" class="hhcul-bgm"/><g filter="url(#iO5397c)"><path fill="url(#iEjVfve)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#ilpqHuW)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#id7oFic)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#iIFcxjc)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#iSScHRd)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#iJXgGxb)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#ix2n82d)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#ixIxGsd)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#itpHSNe)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#iUZi5De)" clip-rule="evenodd" class="qgd8qhspr"/><path fill="url(#ieoKXNM)" clip-rule="evenodd" class="qgd8qhspr"/></g><g filter="url(#iE94kPb)"><path fill="url(#iEz7PjR)" class="oz7q3h5_k"/></g><g filter="url(#i0mzZId)"><path fill="url(#inEhiWb)" class="qz5_yc1lu"/><path fill="url(#igAYUqb)" class="qz5_yc1lu"/></g><g filter="url(#ip8pk1b)"><path class="zomgdti7p"/><path fill="url(#i1EzNni)" class="q26cnlbgb"/></g><g filter="url(#iK7wTCU)"><path class="avwx4yb0i"/><path fill="url(#iDVtYce)" class="y1k99cbut"/></g><g filter="url(#iUuYPWb)"><path fill="url(#i2YBr0B)" class="jg9u_i68n"/><path fill="url(#iFTEB1b)" class="jg9u_i68n"/><path fill="url(#iPUGl3d)" class="jg9u_i68n"/><path fill="url(#iQyANxc)" class="jg9u_i68n"/><path fill="url(#iTsPiUd)" class="jg9u_i68n"/><path fill="url(#iruk4GY)" class="jg9u_i68n"/><path fill="url(#iKFABwc)" class="jg9u_i68n"/></g><path fill="url(#ix6G2Qb)" class="jg9u_i68n"/><path fill="url(#ikDC3hb)" class="jg9u_i68n"/><g filter="url(#ir9J9Ud)"><path class="u1eqt8bnr"/></g><g filter="url(#iVIcO0U)"><path class="ijmb2tejy"/><path fill="url(#iI8Uh6b)" class="zaddkybue"/><path fill="url(#ibG83fe)" class="zaddkybue"/><path fill="url(#iJd3h6d)" class="zaddkybue"/><path fill="url(#i4JOOJc)" class="zaddkybue"/></g><path fill="url(#i0flOlc)" class="zaddkybue"/><path fill="url(#iaosvxd)" class="zaddkybue"/><path stroke="url(#iOzqzBb)" class="gxzn9pboz"/><g filter="url(#isFj8kd)"><path class="cjm5gub7k"/></g><g filter="url(#icvgTKb)"><path class="gsrveacue"/></g><g filter="url(#iUKCydd)"><path class="q7ujs8cwq"/></g><g filter="url(#iW2nnhb)"><path clip-rule="evenodd" class="h3lz-3bxv"/></g><path class="j3m40acsp"/><path fill="url(#iPNDVzQ)" class="sbzc-bn5k"/><path class="r3hbhdw-f"/><g filter="url(#i1L3mee)"><path class="lwy8oiq2y"/><path fill="url(#iqJsblY)" class="qnnqb-bqj"/></g><g filter="url(#ity2CPb)"><path fill="url(#ihgLMKo)" class="nxhx2h07b"/></g><path class="jy_64mb5p"/><path fill="url(#iGrL95Q)" class="i-b3l-24w"/><path class="s_fxzpt1w"/><g filter="url(#iozGnOd)"><path fill="url(#itm9chc)" class="fkqvtnsyo"/></g><g filter="url(#iL628WX)"><ellipse transform="rotate(-27.914 13.547 9.85)" class="qwpmb2k3w"/><ellipse fill="url(#iuiyo9b)" transform="rotate(-27.914 13.547 9.85)" class="j8gttpghw"/></g><g filter="url(#i7rYExd)"><path class="rfd5brktr"/></g><g filter="url(#igDDG8w)"><path class="z85f2il_g"/></g><g filter="url(#itQheDc)"><path class="xnyhlmbxo"/><path fill="url(#icC8sCe)" class="ao4xfqb8b"/></g><g filter="url(#iCIzMPe)"><path class="t1pka12ra"/><path fill="url(#iOoSvGd)" class="bu8yb5vhv"/><path fill="url(#ijWF5ld)" class="bu8yb5vhv"/></g><g filter="url(#irYQmie)"><path stroke="url(#i29vUFc)" class="mix0nwblp"/></g><g filter="url(#i591hbb)"><path class="h7doxoh5u"/></g><g filter="url(#iuxs3El)"><path fill="url(#iEop8sb)" class="mrzjujb4t"/><path fill="url(#iF1gVqc)" class="mrzjujb4t"/><path fill="url(#ioaqHwe)" class="mrzjujb4t"/><path fill="url(#i5fpt3d)" class="mrzjujb4t"/><path fill="url(#iJKzsvb)" class="mrzjujb4t"/><path fill="url(#i868E7b)" class="mrzjujb4t"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="iO45OWc" cx="0" cy="0" r="1" gradientTransform="rotate(-156.777 5.83 14.427)scale(2.6864 2.91777)" gradientUnits="userSpaceOnUse"><stop class="ina1t94tm"/><stop offset="1" class="gl470lbeq"/></radialGradient><radialGradient id="iuQTVIb" cx="0" cy="0" r="1" gradientTransform="rotate(177.157 2.332 14.976)scale(3.35044 4.79049)" gradientUnits="userSpaceOnUse"><stop offset=".764" class="f65wxmfgp"/><stop offset=".927" class="iwc2szfpk"/></radialGradient><radialGradient id="iFw5Zzd" cx="0" cy="0" r="1" gradientTransform="rotate(142.141 -1.79 14.432)scale(2.29569 2.48045)" gradientUnits="userSpaceOnUse"><stop class="z9sgh-b_k"/><stop offset="1" class="wpv14ybvl"/></radialGradient><radialGradient id="iquoPDd" cx="0" cy="0" r="1" gradientTransform="matrix(5.64062 -3.71875 1.03844 1.57511 27.091 30.084)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="phpmogblj"/><stop offset="1" class="vcl0nfbxz"/></radialGradient><radialGradient id="ilpqHuW" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.698 13.044)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="id7oFic" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.883 13.313)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iIFcxjc" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.918 8.139)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iSScHRd" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.354 7.624)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iJXgGxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.48 2.485)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="ix2n82d" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.971 6.804)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="ixIxGsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.51 9.692)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="itpHSNe" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.646 7.966)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iUZi5De" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.962 -3.787)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ieoKXNM" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.858 9.656)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="inEhiWb" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 23.16 -17.216)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="igAYUqb" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.07 8.863)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="i1EzNni" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.392 10.656)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iDVtYce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.4 10.544)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="i2YBr0B" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 18.86 10.006)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="iFTEB1b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.252 11.368)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iPUGl3d" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.62 17.334)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iQyANxc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.72467 -13.4232 0 16 9.789)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="pfelasdwq"/><stop offset=".966" class="ovksowthx"/></radialGradient><radialGradient id="iTsPiUd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.335 6.734)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="iruk4GY" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.301 9.588)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iKFABwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.924 9.359)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ix6G2Qb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.096 11.075)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="ikDC3hb" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.815 4.008)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="iI8Uh6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.785 11.802)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="i4JOOJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.545 12.014)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iaosvxd" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 6.417 8.25)scale(1.66326 1.99898)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="g4eeotb8x"/><stop offset="1" class="szwt30ajm"/></radialGradient><radialGradient id="iPNDVzQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 9.947)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iqJsblY" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.954 10.03)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGrL95Q" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 9.947)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iuiyo9b" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.77 -1.578)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="icC8sCe" cx="0" cy="0" r="1" gradientTransform="rotate(-65.391 11.267 -4.143)scale(3.03069 1.55043)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iOoSvGd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.132 6.94)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ijWF5ld" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 16.21 2.988)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="iF1gVqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.032)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="i868E7b" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.625)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="ix0aLxe" x1="8.815" x2="23.191" y1="15.283" y2="15.283" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iFopWnc" x1="8.815" x2="23.191" y1="15.253" y2="15.253" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iaYeuCc" x1="26.607" x2="27.302" y1="28.803" y2="28.803" gradientUnits="userSpaceOnUse"><stop class="pfqkh_b6e"/><stop offset="1" class="q1cl32x8o"/><stop offset="1" class="fm6jtfbaq"/></linearGradient><linearGradient id="iYHxild" x1="10.918" x2="1.428" y1="23.968" y2="24.009" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ixi72Gc" x1="22.998" x2="28.652" y1="23.985" y2="23.985" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="iEjVfve" x1="20.693" x2="13.888" y1="3.591" y2="16.195" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iEz7PjR" x1="9.705" x2="12.665" y1="10.631" y2="10.631" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="ibG83fe" x1="15.061" x2="16" y1="11.875" y2="11.875" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iJd3h6d" x1="16" x2="16" y1="12.674" y2="12.063" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="i0flOlc" x1="16.078" x2="16.078" y1="12.648" y2="12.508" gradientUnits="userSpaceOnUse"><stop class="szwt30ajm"/><stop offset="1" class="g4eeotb8x"/></linearGradient><linearGradient id="iOzqzBb" x1="14.936" x2="15.397" y1="14.084" y2="13.371" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="ihgLMKo" x1="18.96" x2="18.646" y1="10" y2="10.194" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itm9chc" x1="14.562" x2="14.248" y1="10" y2="10.194" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i29vUFc" x1="13.109" x2="13.653" y1="4.345" y2="5.619" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iEop8sb" x1="7.493" x2="11.284" y1="19.719" y2="30.77" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="ioaqHwe" x1="16" x2="16" y1="15.984" y2="17.344" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="i5fpt3d" x1="5" x2="6.055" y1="24.219" y2="24.219" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="iJKzsvb" x1="27" x2="25.524" y1="25.157" y2="25.157" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="iO5397c" width="15.268" height="15.768" x="8.491" y="1.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/></filter><filter id="iE94kPb" width="3.368" height="3.218" x="9.705" y="8.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/></filter><filter id="i0mzZId" width="3.218" height="3.468" x="19.218" y="8.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/></filter><filter id="ip8pk1b" width="3.148" height="3.148" x="19.253" y="8.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".25"/></filter><filter id="iK7wTCU" width="2.948" height="2.948" x="9.86" y="9.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".2"/></filter><filter id="iUuYPWb" width="10.191" height="11.277" x="10.905" y="5.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/></filter><filter id="ir9J9Ud" width="2.877" height="3.682" x="14.399" y="9.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".25"/></filter><filter id="iVIcO0U" width="2.377" height="3.182" x="14.811" y="9.65" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".125"/></filter><filter id="isFj8kd" width="3.001" height="1.285" x="16.942" y="9.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/></filter><filter id="icvgTKb" width="3.001" height="1.285" x="12.057" y="9.139" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/></filter><filter id="iUKCydd" width="2.453" height="1.091" x="12.192" y="7.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/></filter><filter id="iW2nnhb" width="2.453" height="1.091" x="17.609" y="7.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/></filter><filter id="i1L3mee" width=".787" height=".696" x="17.448" y="9.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".05"/></filter><filter id="ity2CPb" width=".891" height=".913" x="18.288" y="9.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".1"/></filter><filter id="iozGnOd" width=".986" height="1.04" x="13.845" y="9.518" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".1"/></filter><filter id="iL628WX" width=".913" height=".705" x="13.09" y="9.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".05"/></filter><filter id="i7rYExd" width="2.261" height=".978" x="17.64" y="7.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".1"/></filter><filter id="igDDG8w" width="2.261" height=".978" x="12.188" y="7.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".1"/></filter><filter id="itQheDc" width="4.212" height="4.513" x="9.746" y="3.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/><feGaussianBlur result="effect2_foregroundBlur_3_1290" stdDeviation=".15"/></filter><filter id="iCIzMPe" width="8.767" height="5.782" x="12.83" y="2.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/><feGaussianBlur result="effect2_foregroundBlur_3_1290" stdDeviation=".125"/></filter><filter id="irYQmie" width="1.145" height="2.31" x="12.809" y="3.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".1"/></filter><filter id="i591hbb" width="6.427" height="3.372" x="15.418" y="4.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_1290" stdDeviation=".375"/></filter><filter id="iuxs3El" width="22" height="14.1" x="5" y="15.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_1290"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-technologist-light" /></template>
<style>
.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a1q-0ubvc {
  d: path("M8.329 29.985q.004-.081.004-.163a3.138 3.138 0 1 0-6.271.163z");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.ao4xfqb8b {
  d: path("M10.93 4.555c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.04-.479.05-.668.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.492.109-2.38.845-3.16");
}

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.avwx4yb0i {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.334 11.618a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bu8yb5vhv {
  d: path("M15.397 2.753c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.cjm5gub7k {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.142 9.974c.265-.466.669-.835 1.537-.835c.38 0 .747.105 1.073.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cy4dfghcf {
  fill: var(--svg-color--ffd2b6, #FFD2B6);
  d: path("M29.938 29.985q.005-.081.005-.163a3.138 3.138 0 1 0-6.272.163z");
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f65wxmfgp {
  stop-color: var(--svg-color--ffd1b6, #FFD1B6);
  stop-opacity: 0;
}

.fkqvtnsyo {
  d: path("M14.631 10.257c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.fm6jtfbaq {
  stop-color: var(--svg-color--f5c7ad, #F5C7AD);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.g4eeotb8x {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gl470lbeq {
  stop-color: var(--svg-color--f4c0a9, #F4C0A9);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gsrveacue {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.858 9.974c-.265-.466-.669-.835-1.537-.835c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

.gxzn9pboz {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.602 13.066c.404.216.885.34 1.398.34c.518 0 .994-.124 1.398-.34a.205.205 0 0 1 .247.041c.059.062.08.16.022.25m-3.065-.29l3.023.263m-3.023-.264a.204.204 0 0 0-.248.044a.196.196 0 0 0-.02.247m.268-.29l-.227.263m3.292.027l-.042-.027m.042.027l-.042-.027m.042.027a1.982 1.982 0 0 1-3.333 0m3.29-.027a1.932 1.932 0 0 1-3.249 0m-.041.027l.041-.027m-.041.027l.041-.027");
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h3lz-3bxv {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.732 8.308l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .559.238l.009.005z");
}

.h7doxoh5u {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.406 6.363l-1.425.262a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.hhcul-bgm {
  d: path("M23 17.994v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i-b3l-24w {
  d: path("M13.816 9.47a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.893");
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.ijmb2tejy {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.618 10.182l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.ina1t94tm {
  stop-color: var(--svg-color--dfa49e, #DFA49E);
}

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.iwc2szfpk {
  stop-color: var(--svg-color--ffd1b6, #FFD1B6);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j3m40acsp {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.198c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.j8gttpghw {
  cx: 13.547px;
  cy: 9.851px;
  rx: 0.39px;
  ry: 0.197px;
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jg9u_i68n {
  d: path("M10.913 9.28h.012l-.01-.264l-.01-.306c.02-.95.574-1.317.81-1.44q.023-.007.051-.02l.051-.02a2.3 2.3 0 0 0 1.19-1.234l.082-.194a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.136 1.332l-.12 3.073c-.122 2.803-2.311 4.685-4.982 4.685s-4.86-1.882-4.984-4.685z");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jy_64mb5p {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.198c-.653 0-1.205.45-1.355 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kps7ecbkn {
  d: path("M16.025 15.254h-.04c.1 0 .19 0 .29.01c-.08-.01-.17-.01-.25-.01");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lwy8oiq2y {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.658c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
}

.mix0nwblp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.109 4.002c.023.243.234 1.156.544 1.71");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mrzjujb4t {
  d: path("M26.03 15.984H5.97a.97.97 0 0 0-.97.97v13.03h22v-13.03a.97.97 0 0 0-.97-.97");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.nxhx2h07b {
  d: path("M18.979 10.244a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.nzepf2bjg {
  d: path("M16.355 15.254c.25.01.51.03.77.05c-.26-.02-.51-.04-.77-.05");
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.ovksowthx {
  stop-color: var(--svg-color--c37d95, #C37D95);
}

.oz7q3h5_k {
  d: path("M11.314 12.153a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pfelasdwq {
  stop-color: var(--svg-color--dd9fa2, #DD9FA2);
  stop-opacity: 0;
}

.pfqkh_b6e {
  stop-color: var(--svg-color--f5c7ad, #F5C7AD);
}

.phpmogblj {
  stop-color: var(--svg-color--ffe6cb, #FFE6CB);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.pt1lol2at {
  d: path("M29.938 29.985q.005-.081.005-.163a3.138 3.138 0 1 0-6.272.163z");
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.q1cl32x8o {
  stop-color: var(--svg-color--b38f78, #B38F78);
  stop-opacity: 0;
}

.q26cnlbgb {
  d: path("M20.827 11.618a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.q7ujs8cwq {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.602 8.766l-.004.002a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.181z");
}

.qgd8qhspr {
  fill-rule: evenodd;
  d: path("M23.185 11.953c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232A3.3 3.3 0 0 0 16 2.015a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.232q-.043 0-.085.002a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 2.894-4.625a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.194a2.3 2.3 0 0 1-1.292 1.276c-.236.122-.79.49-.81 1.438l.01.307z");
}

.qnnqb-bqj {
  d: path("M18.118 9.658c.064.085-.069.189-.22.302s-.263.192-.327.107c-.063-.085.008-.245.159-.358c.15-.113.325-.136.388-.05");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qwpmb2k3w {
  cx: 13.547px;
  cy: 9.851px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.qz5_yc1lu {
  d: path("M20.827 12.153a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.r3hbhdw-f {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.362c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.rfd5brktr {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.94 8.17c.322-.078 1.124-.038 1.66.345");
}

.s_fxzpt1w {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.362a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .061-.235");
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sbzc-bn5k {
  d: path("M18.184 9.47a.892.892 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.sddnkbbus {
  d: path("M8.98 17.984a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.szwt30ajm {
  stop-color: var(--svg-color--cc8c8d, #CC8C8D);
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.t1pka12ra {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.397 2.753c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.u1eqt8bnr {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.607 10.32l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.493-.376-.613 0");
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vcl0nfbxz {
  stop-color: var(--svg-color--ffe6cb, #FFE6CB);
  stop-opacity: 0;
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wpv14ybvl {
  stop-color: var(--svg-color--d5a58f, #D5A58F);
  stop-opacity: 0;
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xnyhlmbxo {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.93 4.555c.567-.599 1.637-.6 2.132-.51l.396 1.29c-.253-.04-.479.05-.668.235c-.449 1.26-1.99 1.955-2.704 2.145c-.148-1.492.109-2.38.845-3.16");
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y1k99cbut {
  d: path("M11.334 11.618a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z85f2il_g {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.149 8.17c-.323-.078-1.125-.038-1.661.345");
}

.z9sgh-b_k {
  stop-color: var(--svg-color--d5a58f, #D5A58F);
}

.zaddkybue {
  d: path("m15.618 10.182l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zomgdti7p {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.827 11.618a1.074 1.074 0 1 0 0-2.149a1.074 1.074 0 0 0 0 2.149");
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

</style>
