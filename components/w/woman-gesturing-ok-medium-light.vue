<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ioIXcKL)"><path fill="url(#ijJ89kd)" clip-rule="evenodd" class="s7bmlosyp"/><path fill="url(#iTOZkSb)" clip-rule="evenodd" class="s7bmlosyp"/><path fill="url(#idaX9rd)" clip-rule="evenodd" class="s7bmlosyp"/><path fill="url(#ix0IZpd)" clip-rule="evenodd" class="s7bmlosyp"/><path fill="url(#iOaL8Ke)" clip-rule="evenodd" class="s7bmlosyp"/></g><g filter="url(#i4Jw9Nc)"><path fill="url(#itDQJIe)" class="xe94xtbhx"/><path fill="url(#ijpNdMj)" class="xe94xtbhx"/></g><g filter="url(#igNabrb)"><path fill="url(#iECH01b)" class="cob142b7a"/><path fill="url(#ioYkWHc)" class="cob142b7a"/></g><rect fill="url(#iMWRHyv)" class="iuxb-78iw"/><g filter="url(#ie7jQVd)"><path fill="url(#igSvB4J)" class="y0zwm33ay"/><path fill="url(#ispaMAc)" class="y0zwm33ay"/><path fill="url(#ilxYs3d)" class="y0zwm33ay"/><path fill="url(#ie0DMEq)" class="y0zwm33ay"/><path fill="url(#ihH6Xgq)" class="y0zwm33ay"/><path fill="url(#i7lYZAD)" class="y0zwm33ay"/><path fill="url(#if1SLsb)" class="y0zwm33ay"/><path fill="url(#in5Yvad)" class="y0zwm33ay"/><path fill="url(#i33AIMd)" class="y0zwm33ay"/></g><path fill="url(#iyxuAGd)" class="veix-z38b"/><path fill="url(#iTFLztb)" class="veix-z38b"/><path fill="url(#iRnp8Ge)" class="ygsync4_o"/><path fill="url(#iZdzdac)" class="ygsync4_o"/><path fill="url(#ihBX4Ob)" class="r_9_ioa3h"/><path fill="url(#iT9sB5K)" class="r_9_ioa3h"/><path fill="url(#ih88xxe)" class="eim_mrbrv"/><path fill="url(#iB5nmvP)" class="eim_mrbrv"/><g filter="url(#ig2LaMb)"><path fill="url(#ikIICoM)" class="x_mri4gas"/></g><g filter="url(#iNpHeYd)"><path stroke="url(#iRYaePc)" class="yk5l_u5eu"/></g><path stroke="url(#ii8RuQc)" class="djebsbcjo"/><path stroke="url(#ipNuwld)" class="djebsbcjo"/><path stroke="url(#ingEWEy)" class="w930jqbym"/><path stroke="url(#iyIeosc)" class="w930jqbym"/><path stroke="url(#iyzWL7d)" class="w930jqbym"/><path stroke="url(#iuZVj9b)" class="w930jqbym"/><path stroke="url(#i8h9Fdc)" class="cvtf9k6wz"/><path stroke="url(#inSGzvc)" class="cvtf9k6wz"/><path stroke="url(#i9hBjid)" class="lc0lwfbjp"/><path stroke="url(#i0E7FYd)" class="lc0lwfbjp"/><path stroke="url(#ib5kWed)" class="lc0lwfbjp"/><path stroke="url(#iwXD2Dd)" class="lc0lwfbjp"/><path stroke="url(#i0vGyve)" class="zw6cmm23y"/><path stroke="url(#imLLZWb)" class="zw6cmm23y"/><path stroke="url(#iEjqEie)" class="abd3-ibar"/><path stroke="url(#iVPjhAb)" class="abd3-ibar"/><path stroke="url(#idwOqgb)" class="abd3-ibar"/><path stroke="url(#iUYAgce)" class="abd3-ibar"/><path stroke="url(#iNGPBZZ)" class="hockzyb4d"/><path stroke="url(#iy6ah9d)" class="hockzyb4d"/><path stroke="url(#iOXD2Zc)" class="lgc2wbcpd"/><path stroke="url(#iMoeUSN)" class="lgc2wbcpd"/><path stroke="url(#i4xnjeS)" class="lgc2wbcpd"/><path stroke="url(#iMOE9cc)" class="lgc2wbcpd"/><path fill="url(#iPPFs6x)" class="eim_mrbrv"/><path fill="url(#iRYxGic)" class="r_9_ioa3h"/><path fill="url(#iAtPI7M)" class="r_9_ioa3h"/><g filter="url(#iJNDPvb)"><path fill="url(#iWywcDb)" class="t_1lg5u6m"/></g><g filter="url(#i1Ubnue)"><path fill="url(#iJwz2PK)" class="mxc3f8vrk"/></g><g filter="url(#ikB8mKe)"><path class="hc94iu-he"/></g><g filter="url(#i81DOuc)"><path class="w4vl0hbwv"/><path fill="url(#i6VNLhe)" class="vm5gdfbfi"/></g><g filter="url(#iDabsBc)"><path fill="url(#i7ejLwc)" class="i7a7wgkwg"/><path fill="url(#iNngfpb)" class="i7a7wgkwg"/><path fill="url(#i6tbNne)" class="i7a7wgkwg"/><path fill="url(#i9gIoqd)" class="i7a7wgkwg"/><path fill="url(#i0uHNec)" class="i7a7wgkwg"/><path fill="url(#iUHmdFe)" class="i7a7wgkwg"/><path fill="url(#iApmQEe)" class="i7a7wgkwg"/></g><g filter="url(#ifHUR0d)"><path class="n_a-dxbfo"/></g><g filter="url(#i6E5cZN)"><path class="m45fkrc4m"/><path fill="url(#iH88Leb)" class="kaliyjbtv"/><path fill="url(#im6PCxc)" class="kaliyjbtv"/><path fill="url(#iEiK1bd)" class="kaliyjbtv"/></g><path fill="url(#iReZVtc)" class="kaliyjbtv"/><path fill="url(#idL1Leb)" class="kaliyjbtv"/><path stroke="url(#i1Mf5tb)" class="hps8fbc-i"/><g filter="url(#i6vtYWc)"><path class="tdawh5bbz"/></g><g filter="url(#iwmaHcb)"><path class="z2-1r6b6n"/></g><g filter="url(#ijjLBhb)"><path class="fsq_z2d1p"/></g><g filter="url(#indZ1Gb)"><path clip-rule="evenodd" class="do0falb5b"/></g><path class="ionb7nb5v"/><path fill="url(#iCLRTAb)" class="zus0jubvv"/><path class="o0h7dsxoh"/><g filter="url(#iP5Zd8d)"><path class="pa_90u-ol"/><path fill="url(#i4tPGTd)" class="u6j6y_csu"/></g><g filter="url(#ioy0fCd)"><path fill="url(#inBxTIb)" class="n5jqcj8fb"/></g><path class="weeqywbny"/><path fill="url(#iODx89y)" class="crdr8dbkn"/><path class="cnlgdqbpj"/><g filter="url(#iFMehdn)"><path fill="url(#inQB9vF)" class="czt19889x"/></g><g filter="url(#imjcTMb)"><ellipse transform="rotate(-27.914 13.216 14.821)" class="tb96lttad"/><ellipse fill="url(#itmKfAc)" transform="rotate(-27.914 13.216 14.821)" class="lhvqrgi8y"/></g><g filter="url(#i45y2od)"><path class="bgg7wllxq"/></g><g filter="url(#iD6xf1c)"><path class="qznt-abqd"/></g><g filter="url(#iQdBFHe)"><path stroke="url(#igdLYii)" class="kkzatbb2m"/></g><g filter="url(#ifBqiZb)"><path stroke="url(#iPeRnEd)" class="au_vhtphv"/></g><g filter="url(#iJEyJmb)"><path stroke="url(#ikwJ5Ic)" class="qeidnbvzo"/></g><g filter="url(#iVXpZbe)"><path stroke="url(#i7tOmpd)" class="swpl18bdp"/></g><g filter="url(#iW3sqNc)"><path stroke="url(#i1wmsye)" class="pw6_ksacy"/></g><defs><radialGradient id="iTOZkSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.78732 -2.53789 0 10.428 16.079)" gradientUnits="userSpaceOnUse"><stop offset=".333" class="krnumcb_p"/><stop offset="1" class="qrqsclb5b"/></radialGradient><radialGradient id="idaX9rd" cx="0" cy="0" r="1" gradientTransform="rotate(59.036 .475 22.544)scale(5.10208 3.85336)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="dz9xgfbmx"/><stop offset="1" class="r7e1b1b3w"/></radialGradient><radialGradient id="ix0IZpd" cx="0" cy="0" r="1" gradientTransform="rotate(104.928 .17 8.995)scale(5.35253 1.69274)" gradientUnits="userSpaceOnUse"><stop class="ad3qkqbmh"/><stop offset="1" class="uam2yw5lt"/></radialGradient><radialGradient id="iOaL8Ke" cx="0" cy="0" r="1" gradientTransform="matrix(-2.01276 .96876 -3.12367 -6.48993 24.424 13.603)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="vsx6jlb4r"/><stop offset="1" class="tttp5xamw"/></radialGradient><radialGradient id="itDQJIe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0695 2.21877 -1.34677 -1.86315 13.194 8.975)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="foqvobbhc"/><stop offset="1" class="yu2aocvlh"/></radialGradient><radialGradient id="ijpNdMj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48437 -1.0625 2.52858 -3.53253 11.53 10.647)" gradientUnits="userSpaceOnUse"><stop offset=".555" class="j9aoxmbfm"/><stop offset="1" class="rm0kdob8o"/></radialGradient><radialGradient id="iECH01b" cx="0" cy="0" r="1" gradientTransform="rotate(104.389 5.48 11.616)scale(3.38751 7.06854)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="mv8kv7beo"/><stop offset=".796" class="nf4kj_b-k"/></radialGradient><radialGradient id="ioYkWHc" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -3.41726 4.95339 7.5647 16.125 13.475)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="z9knde5sm"/><stop offset="1" class="yykfrpb6q"/></radialGradient><radialGradient id="iMWRHyv" cx="0" cy="0" r="1" gradientTransform="rotate(-129.643 14.383 8.104)scale(3.73397 4.5453)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="p65iqswkh"/><stop offset="1" class="bro2fj6dv"/></radialGradient><radialGradient id="ispaMAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.23667 -6.20284 0 16 20.756)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="w58diel4g"/><stop offset="1" class="v6fmdibat"/></radialGradient><radialGradient id="ilxYs3d" cx="0" cy="0" r="1" gradientTransform="rotate(150.852 12.96 8.252)scale(11.1637 29.6846)" gradientUnits="userSpaceOnUse"><stop class="c74g9abcg"/><stop offset=".435" class="k33dgh0kx"/></radialGradient><radialGradient id="ie0DMEq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.5 .31246 -.61167 -8.80909 8.985 14.584)" gradientUnits="userSpaceOnUse"><stop class="yu6zwbb_v"/><stop offset=".821" class="ksxm-h6au"/></radialGradient><radialGradient id="ihH6Xgq" cx="0" cy="0" r="1" gradientTransform="matrix(-4.24998 6.93751 -7.49713 -4.5928 9.173 6.772)" gradientUnits="userSpaceOnUse"><stop class="jcr-_pt7q"/><stop offset="1" class="vtkyaex6k"/></radialGradient><radialGradient id="i7lYZAD" cx="0" cy="0" r="1" gradientTransform="rotate(120.342 2.473 5.772)scale(1.39468 3.26296)" gradientUnits="userSpaceOnUse"><stop class="t_fx8fd6d"/><stop offset="1" class="u3wjuqrnp"/></radialGradient><radialGradient id="if1SLsb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.13764 1.26425 -3.01923 -5.10504 10.375 18.694)" gradientUnits="userSpaceOnUse"><stop offset=".21" class="rn8u6nbre"/><stop offset="1" class="zigbbibav"/></radialGradient><radialGradient id="in5Yvad" cx="0" cy="0" r="1" gradientTransform="rotate(59.077 7.488 25.014)scale(7.31511 1.73016)" gradientUnits="userSpaceOnUse"><stop class="i01-9l3nj"/><stop offset="1" class="jyzgzgaon"/></radialGradient><radialGradient id="i33AIMd" cx="0" cy="0" r="1" gradientTransform="rotate(54.389 5.84 25.868)scale(1.53089 3.55542)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="p2il30bmc"/><stop offset="1" class="pcu2ods2z"/></radialGradient><radialGradient id="iyxuAGd" cx="0" cy="0" r="1" gradientTransform="rotate(120.064 2.835 5.694)scale(1.3617 3.4441)" gradientUnits="userSpaceOnUse"><stop offset=".356" class="p96ugv3bq"/><stop offset="1" class="kaz2mfb2i"/></radialGradient><radialGradient id="iTFLztb" cx="0" cy="0" r="1" gradientTransform="rotate(118.264 2.99 5.89)scale(.51533 1.79723)" gradientUnits="userSpaceOnUse"><stop offset=".341" class="oc_nn33wh"/><stop offset="1" class="cxw9pac7i"/></radialGradient><radialGradient id="iRnp8Ge" cx="0" cy="0" r="1" gradientTransform="rotate(151.671 11.428 5.79)scale(3.23829 1.54626)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="fqnyw0bnc"/><stop offset="1" class="yysatcquz"/></radialGradient><radialGradient id="iZdzdac" cx="0" cy="0" r="1" gradientTransform="rotate(-27.642 22.401 -43.864)scale(2.22081 .87583)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="dg25vhy-y"/><stop offset="1" class="dn15o-0do"/></radialGradient><radialGradient id="ihBX4Ob" cx="0" cy="0" r="1" gradientTransform="matrix(8.002 -4.48996 1.2352 2.20138 9.235 5.865)" gradientUnits="userSpaceOnUse"><stop offset=".088" class="cxb3glbzc"/><stop offset="1" class="t9spukb2f"/></radialGradient><radialGradient id="iT9sB5K" cx="0" cy="0" r="1" gradientTransform="matrix(.74502 .76747 -3.62255 3.5166 8.584 3.413)" gradientUnits="userSpaceOnUse"><stop class="hdbftdbag"/><stop offset="1" class="gnvn91bpk"/></radialGradient><radialGradient id="ih88xxe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57172 2.16536 -4.16467 -4.94623 24.46 5.257)" gradientUnits="userSpaceOnUse"><stop class="rks0_83_d"/><stop offset="1" class="vua1r5-2d"/></radialGradient><radialGradient id="iB5nmvP" cx="0" cy="0" r="1" gradientTransform="matrix(.27173 1.15625 -2.42824 .57066 20.11 1.85)" gradientUnits="userSpaceOnUse"><stop class="c8sl-2enp"/><stop offset="1" class="lxeh84buj"/></radialGradient><radialGradient id="ikIICoM" cx="0" cy="0" r="1" gradientTransform="rotate(145.941 7.18 16.593)scale(7.39327 7.04413)" gradientUnits="userSpaceOnUse"><stop class="x733f4b8w"/><stop offset="1" class="doo06bbod"/></radialGradient><radialGradient id="ipNuwld" cx="0" cy="0" r="1" gradientTransform="rotate(-97.239 7.9 -3.99)scale(1.45804 6.29236)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="iyzWL7d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.64176 1.91051 -3.15495 -6.01388 20.913 1.013)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="x6vydhb_v"/><stop offset="1" class="dqms9qb3g"/></radialGradient><radialGradient id="iuZVj9b" cx="0" cy="0" r="1" gradientTransform="matrix(.3208 -1.69536 8.52628 1.61337 19.446 3.236)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="inSGzvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.03264 -1.35386 5.89552 -.14215 14.062 3.783)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="ib5kWed" cx="0" cy="0" r="1" gradientTransform="rotate(136.804 9.736 4.212)scale(4.70997 8.35502)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="x6vydhb_v"/><stop offset="1" class="dqms9qb3g"/></radialGradient><radialGradient id="iwXD2Dd" cx="0" cy="0" r="1" gradientTransform="rotate(-86.927 11.324 -7.793)scale(2.40668 8.76587)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="imLLZWb" cx="0" cy="0" r="1" gradientTransform="matrix(.00273 -1.05886 5.57736 .0144 13.901 4.511)" gradientUnits="userSpaceOnUse"><stop offset=".712" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="idwOqgb" cx="0" cy="0" r="1" gradientTransform="rotate(150.94 9.209 4.016)scale(2.77209 4.18391)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="x6vydhb_v"/><stop offset="1" class="dqms9qb3g"/></radialGradient><radialGradient id="iUYAgce" cx="0" cy="0" r="1" gradientTransform="matrix(.09106 -1.00369 6.14439 .55743 18.35 4.439)" gradientUnits="userSpaceOnUse"><stop offset=".708" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="iy6ah9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.01775 -1.34298 3.63064 -.04798 13.474 5.765)" gradientUnits="userSpaceOnUse"><stop offset=".754" class="i5892ackl"/><stop offset="1" class="nt7gwkb2p"/></radialGradient><radialGradient id="i4xnjeS" cx="0" cy="0" r="1" gradientTransform="rotate(127.201 9.028 6.4)scale(3.51838 3.62395)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="x6vydhb_v"/><stop offset=".991" class="e0z1nhb7e"/></radialGradient><radialGradient id="iMOE9cc" cx="0" cy="0" r="1" gradientTransform="matrix(.07604 -1.3001 4.12187 .24108 18.771 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".687" class="ptik26i9i"/><stop offset=".915" class="qp3l4dbyt"/></radialGradient><radialGradient id="iPPFs6x" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07831 4.16712 -14.86837 -3.84744 20.85 2.6)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="lv-cucc-s"/><stop offset=".935" class="o2ym0bbuj"/></radialGradient><radialGradient id="iRYxGic" cx="0" cy="0" r="1" gradientTransform="rotate(-107.186 9 -1.338)scale(1.58646 3.37754)" gradientUnits="userSpaceOnUse"><stop offset=".448" class="y8zuwqb-d"/><stop offset="1" class="de46s3h_f"/></radialGradient><radialGradient id="iAtPI7M" cx="0" cy="0" r="1" gradientTransform="matrix(2.884 -2.16158 .77433 1.03312 8.564 6.55)" gradientUnits="userSpaceOnUse"><stop class="a1et2ybqq"/><stop offset="1" class="jts0ojbqo"/></radialGradient><radialGradient id="iJwz2PK" cx="0" cy="0" r="1" gradientTransform="matrix(2.8005 -1.27296 1.55422 3.41927 20.52 16.095)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="by7_48ces"/><stop offset=".905" class="t-85m-bss"/></radialGradient><radialGradient id="i6VNLhe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36912 0 0 -1.30965 10.726 15.6)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="cqp9_bc3k"/><stop offset="1" class="j-6eibf1s"/></radialGradient><radialGradient id="i7ejLwc" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 7.95 9.604)scale(8.05786 10.7853)" gradientUnits="userSpaceOnUse"><stop class="jlbxk0bjx"/><stop offset="1" class="tnb2fniza"/></radialGradient><radialGradient id="iNngfpb" cx="0" cy="0" r="1" gradientTransform="rotate(152.124 7.099 10.138)scale(2.68532 2.2783)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="i6tbNne" cx="0" cy="0" r="1" gradientTransform="matrix(.94165 -4.55128 5.77473 1.19477 13.523 22.627)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i9gIoqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.48992 -12.0383 0 16.919 15.02)" gradientUnits="userSpaceOnUse"><stop offset=".514" class="pj__wrb2a"/><stop offset="1" class="hiw8w_whp"/></radialGradient><radialGradient id="i0uHNec" cx="0" cy="0" r="1" gradientTransform="matrix(-6.44964 .86744 -1.49347 -11.10432 16.692 17.622)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iUHmdFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29476 1.86137 0 18.565 14.525)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iApmQEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.53017 1.75368 0 13.818 14.623)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iH88Leb" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 14.853 2.144)scale(2.86579 1.63985)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="idL1Leb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44189 1.02993 -1.37952 -1.9313 16.3 16.614)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="iCLRTAb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91283 -1.45196 0 18.43 14.929)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i4tPGTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26094 -.33625 .46294 -.35925 18.174 15.023)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iODx89y" cx="0" cy="0" r="1" gradientTransform="matrix(0 .91284 -1.45197 0 13.52 14.929)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="itmKfAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0087 -.55588 .66819 -.01046 13.198 15.175)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ioIXcKL" width="17.147" height="19.116" x="7.527" y="5.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.662745 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3726"/></filter><filter id="i4Jw9Nc" width="4.172" height="4.852" x="9.322" y="7.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".15"/></filter><filter id="igNabrb" width="10.254" height="7.322" x="12.125" y="6.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".2"/></filter><filter id="ie7jQVd" width="28.403" height="24.735" x="2.048" y="5.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.321569 0 0 0 0 0.25098 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3726"/></filter><filter id="ig2LaMb" width="16.188" height="8.656" x="9.107" y="21.99" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".5"/></filter><filter id="iNpHeYd" width="3.994" height="4.556" x="7.973" y="22.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".25"/></filter><filter id="iJNDPvb" width="3.771" height="3.871" x="8.893" y="13.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.533333 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3726"/></filter><filter id="i1Ubnue" width="3.621" height="3.871" x="19.597" y="13.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.564706 0 0 0 0 0.376471 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3726"/></filter><filter id="ikB8mKe" width="3.417" height="3.417" x="19.698" y="13.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".25"/></filter><filter id="i81DOuc" width="3.217" height="3.217" x="9.117" y="13.992" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".2"/></filter><filter id="iDabsBc" width="11.466" height="12.638" x="10.243" y="10.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3726"/></filter><filter id="ifHUR0d" width="3.112" height="4.017" x="14.237" y="14.532" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".25"/></filter><filter id="i6E5cZN" width="2.612" height="3.517" x="14.67" y="14.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".125"/></filter><filter id="i6vtYWc" width="3.352" height="1.446" x="17.061" y="14.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3726"/></filter><filter id="iwmaHcb" width="3.352" height="1.446" x="11.539" y="14.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3726"/></filter><filter id="ijjLBhb" width="2.735" height="1.202" x="11.691" y="12.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3726"/></filter><filter id="indZ1Gb" width="2.735" height="1.203" x="17.786" y="12.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3726"/></filter><filter id="iP5Zd8d" width=".86" height=".758" x="17.617" y="14.446" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".05"/></filter><filter id="ioy0fCd" width=".953" height=".978" x="18.575" y="14.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".1"/></filter><filter id="iFMehdn" width="1.06" height="1.12" x="13.576" y="14.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".1"/></filter><filter id="imjcTMb" width="1.002" height=".768" x="12.714" y="14.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".05"/></filter><filter id="i45y2od" width="2.469" height="1.025" x="17.858" y="12.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".1"/></filter><filter id="iD6xf1c" width="2.469" height="1.025" x="11.724" y="12.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".1"/></filter><filter id="iQdBFHe" width="1.213" height="2.524" x="12.423" y="7.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".1"/></filter><filter id="ifBqiZb" width="3.508" height="1.177" x="11.275" y="4.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".125"/></filter><filter id="iJEyJmb" width="3.526" height="1.061" x="11.777" y="3.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".125"/></filter><filter id="iVXpZbe" width="3.526" height="1.061" x="12.116" y="2.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".125"/></filter><filter id="iW3sqNc" width="3.504" height="1.198" x="11.147" y="1.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3726" stdDeviation=".125"/></filter><linearGradient id="ijJ89kd" x1="21.256" x2="13.629" y1="7.778" y2="22.404" gradientUnits="userSpaceOnUse"><stop class="sx-enrbww"/><stop offset="1" class="wdp-hebcv"/></linearGradient><linearGradient id="igSvB4J" x1="22.825" x2=".452" y1="30.777" y2="8.828" gradientUnits="userSpaceOnUse"><stop class="ny7dycfhy"/><stop offset="1" class="xhpdgtb4r"/></linearGradient><linearGradient id="iRYaePc" x1="11.267" x2="7.298" y1="23.522" y2="27.647" gradientUnits="userSpaceOnUse"><stop class="zxa4g21za"/><stop offset="1" class="py_i1i4hl"/></linearGradient><linearGradient id="ii8RuQc" x1="14.261" x2="10.736" y1="2.588" y2="4.348" gradientUnits="userSpaceOnUse"><stop offset=".632" class="ph5523b-j"/><stop offset=".827" class="shmkvjbbg"/></linearGradient><linearGradient id="ingEWEy" x1="20.693" x2="21.511" y1="3.024" y2="3.311" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iyIeosc" x1="16.583" x2="21.672" y1="3.146" y2="3.689" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="i8h9Fdc" x1="15.286" x2="12.235" y1="3.297" y2="4.422" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="i9hBjid" x1="19.724" x2="20.597" y1="3.443" y2="3.587" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="i0E7FYd" x1="15.618" x2="20.781" y1="4.258" y2="4.234" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="i0vGyve" x1="14.956" x2="12.465" y1="4.165" y2="5.276" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="iEjqEie" x1="19.214" x2="19.802" y1="4.234" y2="4.398" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iVPjhAb" x1="16.317" x2="19.96" y1="4.575" y2="4.546" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="iNGPBZZ" x1="14.472" x2="11.788" y1="5.127" y2="5.741" gradientUnits="userSpaceOnUse"><stop offset=".805" class="ph5523b-j"/><stop offset="1" class="shmkvjbbg"/></linearGradient><linearGradient id="iOXD2Zc" x1="19.589" x2="20.216" y1="5.254" y2="5.381" gradientUnits="userSpaceOnUse"><stop class="cxjjb1-je"/><stop offset="1" class="bswoa5a7i"/></linearGradient><linearGradient id="iMoeUSN" x1="16.849" x2="20.295" y1="5.882" y2="5.868" gradientUnits="userSpaceOnUse"><stop class="ptbyyggko"/><stop offset=".844" class="w20q0hgpg"/></linearGradient><linearGradient id="iWywcDb" x1="8.893" x2="12.223" y1="15.699" y2="15.699" gradientUnits="userSpaceOnUse"><stop class="n4988dbbk"/><stop offset="1" class="cfetk6bfb"/></linearGradient><linearGradient id="im6PCxc" x1="14.798" x2="15.76" y1="17.036" y2="17.154" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iEiK1bd" x1="15.976" x2="15.976" y1="17.997" y2="17.311" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iReZVtc" x1="16.064" x2="16.064" y1="17.968" y2="17.811" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="i1Mf5tb" x1="15.155" x2="15.665" y1="19.659" y2="18.678" gradientUnits="userSpaceOnUse"><stop class="c4-ln6b1r"/><stop offset="1" class="kfj9zj64e"/></linearGradient><linearGradient id="inBxTIb" x1="19.306" x2="18.953" y1="14.989" y2="15.207" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="inQB9vF" x1="14.357" x2="14.005" y1="14.989" y2="15.207" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="igdLYii" x1="12.723" x2="13.336" y1="8.627" y2="10.06" gradientUnits="userSpaceOnUse"><stop class="d9cogvbmq"/><stop offset="1" class="f-55plbpn"/></linearGradient><linearGradient id="iPeRnEd" x1="14.45" x2="11.399" y1="5.293" y2="6.014" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="ikwJ5Ic" x1="14.964" x2="11.878" y1="4.291" y2="4.847" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="i7tOmpd" x1="15.304" x2="12.218" y1="3.243" y2="3.799" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient><linearGradient id="i1wmsye" x1="14.319" x2="11.275" y1="2.486" y2="3.235" gradientUnits="userSpaceOnUse"><stop class="s45c4_k9i"/><stop offset="1" class="xra9oc37j"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-gesturing-ok-medium-light" /></template>
<style>
.a1et2ybqq {
  stop-color: var(--svg-color--edb090, #EDB090);
}

.abd3-ibar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.498 4.303c-.43-.11-1.281-.203-2.297-.078");
}

.ad3qkqbmh {
  stop-color: var(--svg-color--f0c798, #F0C798);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.au_vhtphv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.65 5.594c.391-.173 1.476-.503 2.758-.41");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bgg7wllxq {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M18.158 12.931c.363-.088 1.265-.044 1.868.387");
}

.bro2fj6dv {
  stop-color: var(--svg-color--905c57, #905C57);
}

.bswoa5a7i {
  stop-color: var(--svg-color--d6a184, #D6A184);
  stop-opacity: 0;
}

.by7_48ces {
  stop-color: var(--svg-color--bc8c86, #BC8C86);
}

.c4-ln6b1r {
  stop-color: var(--svg-color--cc9691, #CC9691);
}

.c74g9abcg {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
}

.c8sl-2enp {
  stop-color: var(--svg-color--cca180, #CCA180);
}

.cfetk6bfb {
  stop-color: var(--svg-color--a9736c, #A9736C);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnlgdqbpj {
  fill: var(--svg-color--000, #000);
  d: path("M14.094 15.396a.573.573 0 0 0-.576-.575a.573.573 0 0 0-.51.84h1.017a.6.6 0 0 0 .069-.265");
}

.cob142b7a {
  d: path("M15.297 6.835c-1.274-.281-2.64 1.075-2.772 1.546c1.735 4.074 4.392 3.36 7.522 3.36c2.028 0 1.93 1.078 1.906 1.578c.39-5.328-3.752-5.843-6.656-6.484");
}

.cqp9_bc3k {
  stop-color: var(--svg-color--a56e65, #A56E65);
  stop-opacity: 0;
}

.crdr8dbkn {
  d: path("M13.518 14.392a1.004 1.004 0 0 0-.967 1.269h1.94a1 1 0 0 0 .036-.265a1.01 1.01 0 0 0-1.009-1.004");
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cvtf9k6wz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.62 3.49c.43-.109 1.65-.273 2.666-.148");
}

.cxb3glbzc {
  stop-color: var(--svg-color--eab594, #EAB594);
}

.cxjjb1-je {
  stop-color: var(--svg-color--d6a184, #D6A184);
}

.cxw9pac7i {
  stop-color: var(--svg-color--7d71ae, #7D71AE);
  stop-opacity: 0;
}

.czt19889x {
  d: path("M14.436 15.278c0-.324-.264-.54-.335-.606l-.325.314l.2.406z");
}

.d9cogvbmq {
  stop-color: var(--svg-color--e1c48e, #E1C48E);
}

.de46s3h_f {
  stop-color: var(--svg-color--d48e7a, #D48E7A);
  stop-opacity: 0;
}

.dg25vhy-y {
  stop-color: var(--svg-color--584b8c, #584B8C);
}

.djebsbcjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M11.082 3.186c.68-.344 2.469-.57 3.188-.524");
}

.dn15o-0do {
  stop-color: var(--svg-color--584b8c, #584B8C);
  stop-opacity: 0;
}

.do0falb5b {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m20.174 13.085l-.155.26za.302.302 0 0 1-.31.518l-.005-.003l-.025-.013l-.102-.052a3 3 0 0 0-.386-.152a2.56 2.56 0 0 0-1.206-.104a.302.302 0 1 1-.105-.594c.578-.102 1.113 0 1.495.123a3.7 3.7 0 0 1 .628.268l.011.006l.003.002z");
}

.doo06bbod {
  stop-color: var(--svg-color--9179cd, #9179CD);
  stop-opacity: 0;
}

.dqms9qb3g {
  stop-color: var(--svg-color--c98b5e, #C98B5E);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dz9xgfbmx {
  stop-color: var(--svg-color--aa9879, #AA9879);
}

.e0z1nhb7e {
  stop-color: var(--svg-color--cc9167, #CC9167);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.eim_mrbrv {
  d: path("M22.643 3.084a61 61 0 0 1 1.79 1.611a.08.08 0 0 1 .026.054c.033.573-1.968 1.625-3.038 2.013a.1.1 0 0 1-.034.006c-.941-.005-1.105-.372-1.736-.664c-.727-.336-1.477-.309-1.867-.309c-.391 0-.602-.219-.696-.414c-.064-.133-.064-.316.03-.523a.63.63 0 0 1-.442-.282a.64.64 0 0 1-.057-.625c-.156-.062-.336-.304-.312-.648c.037-.538.562-.662.781-.656h.164c-.012-.55.585-.6.815-.575l1.717.098a.98.98 0 0 1 .765-.133c.432.123 1.263.339 2.094 1.047");
}

.f-55plbpn {
  stop-color: var(--svg-color--caa179, #CAA179);
}

.foqvobbhc {
  stop-color: var(--svg-color--f8d7ad, #F8D7AD);
}

.fqnyw0bnc {
  stop-color: var(--svg-color--8378b6, #8378B6);
}

.fsq_z2d1p {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m12.153 13.6l-.005.003a.302.302 0 0 1-.31-.518h.002l.003-.003l.01-.006l.037-.02q.047-.026.13-.066c.111-.053.27-.12.462-.182c.382-.122.917-.225 1.495-.123a.302.302 0 0 1-.105.594c-.45-.079-.88 0-1.207.104a3 3 0 0 0-.512.217");
}

.ft5dv1b6b {
  fill: none;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gnvn91bpk {
  stop-color: var(--svg-color--c69a7a, #C69A7A);
  stop-opacity: 0;
}

.hc94iu-he {
  fill: var(--svg-color--a6766a, #A6766A);
  d: path("M21.407 16.809a1.209 1.209 0 1 0 0-2.417a1.209 1.209 0 0 0 0 2.417");
}

.hdbftdbag {
  stop-color: var(--svg-color--c69a7a, #C69A7A);
}

.hiw8w_whp {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
}

.hockzyb4d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.3 5.381c.274-.102 1.102-.305 2.172-.242");
}

.hps8fbc-i {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.4 18.444a.224.224 0 0 0-.271.048a.214.214 0 0 0-.023.27a2.224 2.224 0 0 0 3.74 0a.22.22 0 0 0-.023-.273a.224.224 0 0 0-.27-.045h-.001a3.34 3.34 0 0 1-1.576.382c-.578 0-1.12-.139-1.576-.382Z");
}

.i01-9l3nj {
  stop-color: var(--svg-color--9478d2, #9478D2);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.i5892ackl {
  stop-color: var(--svg-color--d39869, #D39869);
  stop-opacity: 0;
}

.i7a7wgkwg {
  d: path("M10.252 14.18h.014l-.012-.299l-.011-.344c.023-1.068.646-1.48.911-1.619l.058-.023l.058-.023a2.6 2.6 0 0 0 1.338-1.389l.092-.218a.297.297 0 0 1 .52-.057a4.35 4.35 0 0 0 3.588 1.883h3.623c.202 0 1.217.098 1.278 1.499l-.134 3.457c-.139 3.153-2.6 5.27-5.607 5.27c-3.005 0-5.468-2.117-5.606-5.27z");
}

.ionb7nb5v {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.666 14.086c.735 0 1.355.507 1.524 1.191c.05.197-.1.384-.3.384h-2.511a.26.26 0 0 1-.256-.306a1.57 1.57 0 0 1 1.543-1.269");
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.iuxb-78iw {
  width: 4.615px;
  height: 6.587px;
  x: 13.668px;
  y: 17.985px;
  rx: 2.307px;
}

.j-6eibf1s {
  stop-color: var(--svg-color--a56e65, #A56E65);
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.j9aoxmbfm {
  stop-color: var(--svg-color--cfae8c, #CFAE8C);
  stop-opacity: 0;
}

.jcr-_pt7q {
  stop-color: var(--svg-color--7357b2, #7357B2);
}

.jlbxk0bjx {
  stop-color: var(--svg-color--f4bc98, #F4BC98);
}

.jts0ojbqo {
  stop-color: var(--svg-color--edb090, #EDB090);
  stop-opacity: 0;
}

.jyzgzgaon {
  stop-color: var(--svg-color--9478d2, #9478D2);
  stop-opacity: 0;
}

.k33dgh0kx {
  stop-color: var(--svg-color--9d7dde, #9D7DDE);
  stop-opacity: 0;
}

.kaliyjbtv {
  d: path("m15.546 15.194l-.598 1.913a.607.607 0 0 0 .585.787h.885c.415 0 .708-.4.586-.787l-.598-1.913c-.128-.424-.726-.424-.86 0");
}

.kaz2mfb2i {
  stop-color: var(--svg-color--4c4181, #4C4181);
}

.kfj9zj64e {
  stop-color: var(--svg-color--cc9691, #CC9691);
  stop-opacity: 0;
}

.kkzatbb2m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.723 8.24c.026.274.264 1.301.613 1.924");
}

.krnumcb_p {
  stop-color: var(--svg-color--a07564, #A07564);
}

.ksxm-h6au {
  stop-color: var(--svg-color--65509d, #65509D);
  stop-opacity: 0;
}

.lc0lwfbjp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M20.126 3.608c-.43-.11-2.375-.477-3.255-.266");
}

.lgc2wbcpd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M19.857 5.381c-.273-.102-1.101-.305-2.171-.242");
}

.lhvqrgi8y {
  cx: 13.216px;
  cy: 14.821px;
  rx: 0.438px;
  ry: 0.222px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lv-cucc-s {
  stop-color: var(--svg-color--ce886b, #CE886B);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lxeh84buj {
  stop-color: var(--svg-color--cca180, #CCA180);
  stop-opacity: 0;
}

.m45fkrc4m {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.546 15.194l-.598 1.913a.607.607 0 0 0 .585.787h.885c.415 0 .708-.4.586-.787l-.598-1.913c-.128-.424-.726-.424-.86 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mxc3f8vrk {
  d: path("M21.407 17.41a1.81 1.81 0 1 0 0-3.62a1.81 1.81 0 0 0 0 3.62");
}

.n_a-dxbfo {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.534 15.35l-.769 1.913a.607.607 0 0 0 .586.786h.884a.608.608 0 0 0 .586-.786l-.598-1.913c-.128-.424-.555-.424-.689 0");
}

.n4988dbbk {
  stop-color: var(--svg-color--a77066, #A77066);
}

.n5jqcj8fb {
  d: path("M19.328 15.264a.95.95 0 0 0-.26-.52l-.293.32l.132.257z");
}

.nf4kj_b-k {
  stop-color: var(--svg-color--f2d49e, #F2D49E);
}

.nt7gwkb2p {
  stop-color: var(--svg-color--d39869, #D39869);
}

.ny7dycfhy {
  stop-color: var(--svg-color--7767af, #7767AF);
}

.o0h7dsxoh {
  fill: var(--svg-color--000, #000);
  d: path("M17.858 15.396c0-.32.256-.575.575-.575a.573.573 0 0 1 .511.84h-1.017a.5.5 0 0 1-.069-.265");
}

.o2ym0bbuj {
  stop-color: var(--svg-color--ce886b, #CE886B);
}

.oc_nn33wh {
  stop-color: var(--svg-color--7d71ae, #7D71AE);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p2il30bmc {
  stop-color: var(--svg-color--694eab, #694EAB);
}

.p65iqswkh {
  stop-color: var(--svg-color--e6b29b, #E6B29B);
}

.p96ugv3bq {
  stop-color: var(--svg-color--6d5ea5, #6D5EA5);
}

.pa_90u-ol {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.36 14.604c.07.096-.079.213-.249.34s-.296.216-.367.12c-.072-.095.008-.276.178-.403s.366-.152.437-.057");
}

.pcu2ods2z {
  stop-color: var(--svg-color--694eab, #694EAB);
  stop-opacity: 0;
}

.ph5523b-j {
  stop-color: var(--svg-color--e9b895, #E9B895);
}

.pj__wrb2a {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ptbyyggko {
  stop-color: var(--svg-color--d09472, #D09472);
}

.ptik26i9i {
  stop-color: var(--svg-color--c19471, #C19471);
  stop-opacity: 0;
}

.pw6_ksacy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.522 2.814c.39-.177 1.471-.517 2.755-.436");
}

.py_i1i4hl {
  stop-color: var(--svg-color--8477ba, #8477BA);
  stop-opacity: 0;
}

.qeidnbvzo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.152 4.442c.4-.152 1.5-.423 2.776-.262");
}

.qp3l4dbyt {
  stop-color: var(--svg-color--c19471, #C19471);
}

.qrqsclb5b {
  stop-color: var(--svg-color--a07564, #A07564);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qznt-abqd {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.893 12.931c-.363-.088-1.266-.044-1.869.387");
}

.r_9_ioa3h {
  d: path("M9.515 3.084a61 61 0 0 0-1.79 1.611a.08.08 0 0 0-.027.054c-.033.573 1.969 1.625 3.039 2.013q.016.006.034.006c.941-.005 1.104-.372 1.736-.664c.726-.336 1.476-.309 1.867-.309c.39 0 .602-.219.695-.414c.064-.133.065-.316-.029-.523a.63.63 0 0 0 .442-.282a.64.64 0 0 0 .056-.625c.156-.062.337-.304.313-.648c-.038-.538-.563-.662-.782-.656h-.164c.013-.55-.585-.6-.814-.575l-1.717.098a.98.98 0 0 0-.766-.133c-.432.123-1.263.339-2.093 1.047");
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r7e1b1b3w {
  stop-color: var(--svg-color--aa9879, #AA9879);
  stop-opacity: 0;
}

.rks0_83_d {
  stop-color: var(--svg-color--f5c39b, #F5C39B);
}

.rm0kdob8o {
  stop-color: var(--svg-color--9a8264, #9A8264);
}

.rn8u6nbre {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
}

.s45c4_k9i {
  stop-color: var(--svg-color--f7cbb0, #F7CBB0);
}

.s7bmlosyp {
  fill-rule: evenodd;
  d: path("M24.06 17.187a3.64 3.64 0 0 0 .364-1.606c0-.526-.108-1.019-.302-1.469h.006a3.6 3.6 0 0 0-.316-.577l-.003-.003a3.65 3.65 0 0 1-.592-1.993v-.011a3.713 3.713 0 0 0-3.711-3.712a.6.6 0 0 1-.513-.262a3.72 3.72 0 0 0-3.017-1.549a3.72 3.72 0 0 0-3.018 1.549a.64.64 0 0 1-.512.262h-.096a3.713 3.713 0 0 0-3.616 3.712v.011c0 .706-.205 1.4-.592 1.993l-.003.004a3.71 3.71 0 0 0-.248 3.65c.08.16.08.354 0 .513a3.7 3.7 0 0 0-.364 1.583c0 2.004 1.617 5.09 3.62 5.09h9.657c2.004 0 3.62-3.086 3.62-5.09c0-.57-.136-1.105-.364-1.583a.58.58 0 0 1 0-.512M10.266 14.18h-.014l1.349 2.65c.138 3.153 1.369 0 4.375 0c3.005 0 4.316 3.51 4.455.357l1.278-3.598c-.06-1.4-1.076-1.498-1.278-1.498h-3.623c-1.43 0-2.78-.7-3.588-1.883a.297.297 0 0 0-.52.057l-.092.218a2.6 2.6 0 0 1-1.396 1.412l-.058.023c-.265.138-.888.551-.911 1.619l.011.344z");
}

.shmkvjbbg {
  stop-color: var(--svg-color--e9b895, #E9B895);
  stop-opacity: 0;
}

.swpl18bdp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.491 3.394c.4-.152 1.5-.423 2.777-.262");
}

.sx-enrbww {
  stop-color: var(--svg-color--e4cda0, #E4CDA0);
}

.t_1lg5u6m {
  d: path("M10.704 17.41a1.81 1.81 0 1 0 0-3.62a1.81 1.81 0 0 0 0 3.62");
}

.t_fx8fd6d {
  stop-color: var(--svg-color--9179c9, #9179C9);
}

.t-85m-bss {
  stop-color: var(--svg-color--a07064, #A07064);
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.t9spukb2f {
  stop-color: var(--svg-color--ddaf8a, #DDAF8A);
}

.tb96lttad {
  cx: 13.216px;
  cy: 14.821px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.438px;
  ry: 0.222px;
}

.tdawh5bbz {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.26 14.96c.3-.525.753-.94 1.73-.94c.428 0 .84.119 1.208.415c.302.244.261.557.027.674l-.625.357c-.734-.237-1.545-.269-2.34-.506");
}

.tnb2fniza {
  stop-color: var(--svg-color--b98478, #B98478);
}

.tttp5xamw {
  stop-color: var(--svg-color--edd4a5, #EDD4A5);
  stop-opacity: 0;
}

.u3wjuqrnp {
  stop-color: var(--svg-color--9179c9, #9179C9);
  stop-opacity: 0;
}

.u6j6y_csu {
  d: path("M18.36 14.604c.07.096-.079.213-.249.34s-.296.216-.367.12c-.072-.095.008-.276.178-.403s.366-.152.437-.057");
}

.uam2yw5lt {
  stop-color: var(--svg-color--f0c798, #F0C798);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v6fmdibat {
  stop-color: var(--svg-color--312654, #312654);
  stop-opacity: 0;
}

.veix-z38b {
  d: path("M7.397 4.635L6.97 5.3a.24.24 0 0 0 .01.278c.9 1.155 2.374 1.801 3.283 2.087a.244.244 0 0 0 .281-.107c.15-.248.354-.585.409-.69c.069-.131-.029-.232-.086-.265L7.85 4.775l.125-.273c-.35-.106-.53.044-.578.133");
}

.vm5gdfbfi {
  d: path("M10.726 16.809a1.209 1.209 0 1 0 0-2.417a1.209 1.209 0 0 0 0 2.417");
}

.vsx6jlb4r {
  stop-color: var(--svg-color--edd4a5, #EDD4A5);
}

.vtkyaex6k {
  stop-color: var(--svg-color--7357b2, #7357B2);
  stop-opacity: 0;
}

.vua1r5-2d {
  stop-color: var(--svg-color--d5a482, #D5A482);
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w20q0hgpg {
  stop-color: var(--svg-color--d09472, #D09472);
  stop-opacity: 0;
}

.w4vl0hbwv {
  fill: var(--svg-color--9c645c, #9C645C);
  d: path("M10.726 16.809a1.209 1.209 0 1 0 0-2.417a1.209 1.209 0 0 0 0 2.417");
}

.w58diel4g {
  stop-color: var(--svg-color--312654, #312654);
}

.w930jqbym {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M21.076 3.186c-.68-.344-2.47-.57-3.188-.524");
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wdp-hebcv {
  stop-color: var(--svg-color--8e6653, #8E6653);
}

.weeqywbny {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.286 14.086c-.735 0-1.356.507-1.525 1.191c-.05.197.1.384.301.384h2.51a.26.26 0 0 0 .256-.306a1.576 1.576 0 0 0-1.542-1.269");
}

.x_mri4gas {
  d: path("M23.873 27.147c-1.95-1.2-3.036-3.417-3.36-4.157c-5.174 0-9.28 1.97-10.406 6.657h14.188c0-.9-.156-1.938-.422-2.5");
}

.x6vydhb_v {
  stop-color: var(--svg-color--cc9167, #CC9167);
  stop-opacity: 0;
}

.x733f4b8w {
  stop-color: var(--svg-color--9179cd, #9179CD);
}

.xe94xtbhx {
  d: path("M10.47 8.834c.698-.622 1.706-.629 2.271-.528l.453 1.452c-.289-.044-.547.057-.764.264c-.513 1.418-2.175 1.769-2.612 2.488c-.17-1.679-.556-2.601.651-3.676");
}

.xhpdgtb4r {
  stop-color: var(--svg-color--5e4998, #5E4998);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xra9oc37j {
  stop-color: var(--svg-color--f7cbb0, #F7CBB0);
  stop-opacity: 0;
}

.y0zwm33ay {
  d: path("M6.367 5.28c.269-.07.742.028.945.085L10.5 7.53c.352.415.19.967.055 1.18L8.48 12.221a4.5 4.5 0 0 0-.11 4.382l2.96 5.634a.37.37 0 0 0 .492.152c.203-.101.82-.33 1.323-.515l.524-.195v.586a2.307 2.307 0 1 0 4.614 0v-.684c.672.276 1.662.692 1.894.808a.37.37 0 0 0 .493-.152l2.96-5.634a4.5 4.5 0 0 0-.11-4.382l-2.075-3.512c-.135-.213-.297-.765.055-1.18l3.188-2.164c.203-.057.676-.154.945-.086c.336.086.594.329.812.688c.175.287 1.47 2.48 2.094 3.539c.563.823 1.625 3.088 1.375 5.563c-.1 1.662-.781 3.338-1.11 3.968l-4.132 7.855c-.173.33-.187.719-.08 1.076c.158.529.322 1.28.322 2.022H7.086c0-.743.164-1.493.322-2.022a1.43 1.43 0 0 0-.08-1.076l-4.133-7.855c-.328-.63-1.01-2.306-1.11-3.968c-.25-2.476.813-4.74 1.376-5.563a958 958 0 0 1 2.094-3.54c.218-.358.476-.6.812-.687");
}

.y8zuwqb-d {
  stop-color: var(--svg-color--d48e7a, #D48E7A);
}

.ygsync4_o {
  d: path("m24.76 4.635l.428.666a.24.24 0 0 1-.01.278c-.899 1.155-2.373 1.801-3.283 2.087a.244.244 0 0 1-.28-.107a24 24 0 0 1-.41-.69c-.068-.131.03-.232.087-.265l3.015-1.829l-.125-.273c.35-.106.531.044.578.133");
}

.yk5l_u5eu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.673 26.678c.48-.448 1.669-1.706 2.594-3.156");
}

.yu2aocvlh {
  stop-color: var(--svg-color--bf9486, #BF9486);
}

.yu6zwbb_v {
  stop-color: var(--svg-color--65509d, #65509D);
}

.yykfrpb6q {
  stop-color: var(--svg-color--a18a6b, #A18A6B);
}

.yysatcquz {
  stop-color: var(--svg-color--3d2f68, #3D2F68);
}

.z2-1r6b6n {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.691 14.96c-.299-.525-.753-.94-1.73-.94c-.428 0-.84.119-1.207.415c-.302.244-.262.557-.027.674l.625.357c.733-.237 1.544-.269 2.339-.506");
}

.z9knde5sm {
  stop-color: var(--svg-color--e2c1a0, #E2C1A0);
  stop-opacity: 0;
}

.zigbbibav {
  stop-color: var(--svg-color--4d3e7d, #4D3E7D);
  stop-opacity: 0;
}

.zus0jubvv {
  d: path("M18.433 14.392a1.004 1.004 0 0 1 .968 1.269h-1.94a1.008 1.008 0 0 1 .972-1.269");
}

.zw6cmm23y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M12.66 4.303c.43-.11 1.28-.203 2.296-.078");
}

.zxa4g21za {
  stop-color: var(--svg-color--8477ba, #8477BA);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
