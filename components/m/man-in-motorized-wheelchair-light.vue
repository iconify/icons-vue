<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#imnwJEA)" class="p6_urry8d"/><path fill="url(#inAgBNd)" class="p6_urry8d"/><path fill="url(#ii7timF)" class="p6_urry8d"/><path class="w1w5tgb0x"/><path fill="url(#iVGmY0c)" class="z66hukbak"/><path fill="url(#io9N2mb)" class="z66hukbak"/><path fill="url(#ichRgdd)" class="z66hukbak"/><g filter="url(#ijJfCFe)"><path fill="url(#ixgkPDc)" class="kc35rj-oq"/><path fill="url(#iA75J6b)" class="kc35rj-oq"/><path fill="url(#iAqVh6d)" class="kc35rj-oq"/><path fill="url(#ieKnQFe)" class="kc35rj-oq"/></g><path class="butdkhblz"/><path fill="url(#iuu4j9d)" class="o9_83db5k"/><path fill="url(#ik1Ynre)" class="o9_83db5k"/><path fill="url(#it74J4d)" class="o9_83db5k"/><path fill="url(#iTlw1ze)" class="d06h_8buq"/><path fill="url(#i8EtACb)" class="ri8idabqv"/><path fill="url(#iaibdoc)" class="gqx2wrbhf"/><g filter="url(#iWLMvOp)"><path clip-rule="evenodd" class="jiurw55ug"/><path fill="url(#ibx1NPr)" clip-rule="evenodd" class="ibdgujbbi"/></g><g filter="url(#iORB7fd)"><path stroke="url(#i13oEde)" class="xz-6k3bpg"/></g><circle fill="url(#iGvzzKb)" class="q40uu5bap"/><circle fill="url(#iFNUxrd)" class="q40uu5bap"/><circle fill="url(#iesb7eb)" class="q40uu5bap"/><circle class="kwf7z6buh"/><circle fill="url(#iu9NI8d)" class="mb7aovqiv"/><circle fill="url(#i5U0f5c)" class="mb7aovqiv"/><g filter="url(#i26SDUc)"><path fill="url(#iGAFQ0c)" class="uc2shjbgg"/><path fill="url(#ii4ZWCV)" class="uc2shjbgg"/><path fill="url(#iqA0X9a)" class="uc2shjbgg"/></g><g filter="url(#iIZcOxe)"><path class="hdstylo5p"/><path fill="url(#i2HwWcd)" class="ln49lacxs"/></g><path class="kx0-osb2n"/><path fill="url(#ib3lOhc)" class="zyodnlbru"/><path fill="url(#iRqT9Id)" class="zyodnlbru"/><path fill="url(#i2Fsfdc)" class="zyodnlbru"/><path fill="url(#iFjT9qd)" class="zyodnlbru"/><path fill="url(#irp4HHd)" class="zyodnlbru"/><rect fill="url(#iu56Nre)" transform="rotate(9.205 23.613 6.61)" class="lnq-uwb2f"/><rect fill="url(#iHZFVsa)" transform="rotate(9.205 23.613 6.61)" class="lnq-uwb2f"/><path fill="url(#i7skBKd)" class="aapalwo8e"/><path fill="url(#iEzlkwc)" class="aapalwo8e"/><g filter="url(#itQcZdc)"><path class="wnft2sbxi"/><path fill="url(#iYObvFc)" class="ga7b7ubfr"/><path fill="url(#iaUoEhd)" class="ga7b7ubfr"/></g><path fill="url(#ioygFpd)" class="ga7b7ubfr"/><g filter="url(#iPaVTkb)"><rect class="j6tziiblj"/><rect fill="url(#i9OL0oc)" class="d162jvikx"/><rect fill="url(#iYpPigb)" class="d162jvikx"/></g><rect fill="url(#ifYqZAe)" class="d162jvikx"/><g filter="url(#ioRAUhb)"><path fill="url(#iLslrTU)" class="hi-ljefvf"/></g><path fill="url(#i0XmlAe)" class="hi-ljefvf"/><circle class="b15132bnl"/><g filter="url(#iyidkWb)"><circle class="crgxtfbyy"/></g><circle fill="url(#ian8Fob)" class="entt9mbqv"/><circle fill="url(#i8ZeH5b)" class="n5si-vkmf"/><circle fill="url(#i2izg2d)" class="mplkytb5s"/><g filter="url(#iEFEa8b)"><path clip-rule="evenodd" class="nadkggbux"/></g><path fill="url(#i2LyDpd)" clip-rule="evenodd" class="o-40n7v3x"/><g filter="url(#iXr3xdb)"><circle class="hx49fyb4j"/></g><g filter="url(#igEc5Gd)"><circle class="rva11cbyn"/></g><g filter="url(#irCNqEd)"><path fill="url(#ihvlZNe)" class="b11h0-bme"/></g><path fill="url(#iWtYetd)" class="b11h0-bme"/><path fill="url(#inK3Tfd)" class="b11h0-bme"/><circle fill="url(#ieUWuOc)" class="q9d0l_bnd"/><g filter="url(#i6OQ7mb)"><path clip-rule="evenodd" class="eih5wcbly"/></g><g filter="url(#iLqUfjc)"><path stroke="url(#iVNc7pd)" clip-rule="evenodd" class="uf2kifdvc"/></g><g filter="url(#ibhrQ1b)"><path stroke="url(#iRUjcEb)" clip-rule="evenodd" class="e5nfrccvd"/></g><g filter="url(#iKetFwb)"><path class="sgi6nwbff"/></g><g filter="url(#iSJlK7c)"><path stroke="url(#iiFsHjb)" clip-rule="evenodd" class="h2er9kbhc"/></g><g filter="url(#iXEm7bb)"><circle class="zf01zc1zi"/></g><g filter="url(#iNH6WBd)"><path class="s--8ht3bv"/></g><g filter="url(#i9Mkn7c)"><path class="dp41p39px"/><path fill="url(#icOtgab)" class="cuar4pu2m"/></g><g filter="url(#iowhDCe)"><path class="y1f7q6bmk"/></g><g filter="url(#ikveJ4Y)"><path class="tnmhci3wx"/></g><path fill="url(#itJzvmd)" class="lt84bikqe"/><g filter="url(#ikJp7Pb)"><path fill="url(#iSpq6je)" class="p6c0fhbrq"/><path fill="url(#iIa0KiN)" class="p6c0fhbrq"/><path fill="url(#ipXcT1c)" class="p6c0fhbrq"/><path fill="url(#iVJBCJg)" class="p6c0fhbrq"/></g><g filter="url(#iDdPJUc)"><path fill="url(#iC9hQYW)" class="tittjnbcr"/></g><g filter="url(#ietkBkd)"><path fill="url(#ivRQBrb)" class="tittjnbcr"/><path fill="url(#iA860hc)" class="tittjnbcr"/><path fill="url(#ism8bYK)" class="tittjnbcr"/></g><path fill="url(#iqTdpke)" class="ifgvwhkxh"/><path fill="url(#ihXGu4M)" class="ifgvwhkxh"/><path fill="url(#i1WU6Id)" class="ifgvwhkxh"/><path clip-rule="evenodd" class="zw49qzbqk"/><path class="qzfsgzpkj"/><path fill="url(#idKlvqd)" class="ppt-j6bdy"/><path fill="url(#iMhZRfd)" class="fiobnycwk"/><ellipse fill="url(#iIjUXWd)" transform="rotate(30.509 18.22 5.092)" class="d1q2qt76h"/><g filter="url(#iNCsnOe)"><path clip-rule="evenodd" class="nkpj6tq5u"/></g><path class="bvncjee1j"/><path fill="url(#itoCska)" class="ptiqigyhx"/><path fill="url(#iexsjSd)" class="ptiqigyhx"/><path fill="url(#ik3z59u)" class="ptiqigyhx"/><path fill="url(#imR7Pte)" class="ptiqigyhx"/><path fill="url(#i1sO2rd)" class="ptiqigyhx"/><g filter="url(#iYrVKVb)"><path fill="url(#ix29NMe)" class="ucj-rmbzy"/></g><path class="x6jhwbjfz"/><path fill="url(#ieFIG9c)" class="nkqm-bcwx"/><path fill="url(#ixe3STk)" class="nkqm-bcwx"/><path fill="url(#iLkAOCe)" class="nkqm-bcwx"/><defs><radialGradient id="imnwJEA" cx="0" cy="0" r="1" gradientTransform="matrix(1.69572 .35923 -1.2878 6.07893 19.21 8.931)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nov_osbjm"/><stop offset="1" class="b10rjxgth"/></radialGradient><radialGradient id="inAgBNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.37746 .9231 -.70366 -.28773 21.154 7.474)" gradientUnits="userSpaceOnUse"><stop class="zuv46pbeh"/><stop offset="1" class="a0cytj3vs"/></radialGradient><radialGradient id="iVGmY0c" cx="0" cy="0" r="1" gradientTransform="matrix(4.625 4.75 -5.30937 5.16965 16.085 9.475)" gradientUnits="userSpaceOnUse"><stop offset=".367" class="l-ch5ci-p"/><stop offset="1" class="z-2ie6sne"/></radialGradient><radialGradient id="ichRgdd" cx="0" cy="0" r="1" gradientTransform="matrix(.82524 -4.84513 7.08082 1.20602 19.346 13.286)" gradientUnits="userSpaceOnUse"><stop offset=".918" class="zqylsrrgt"/><stop offset="1" class="j0xqyhb3r"/></radialGradient><radialGradient id="iA75J6b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -1 2.95172 -6.27244 12.148 21.787)" gradientUnits="userSpaceOnUse"><stop class="jzl720bvd"/><stop offset="1" class="zdh48sb9s"/></radialGradient><radialGradient id="iAqVh6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.40625 6.4375 0 18.648 18.068)" gradientUnits="userSpaceOnUse"><stop class="d9q4mwzxt"/><stop offset="1" class="kegmapbvr"/></radialGradient><radialGradient id="ieKnQFe" cx="0" cy="0" r="1" gradientTransform="rotate(11.535 -92.654 56.199)scale(1.56281 6.59576)" gradientUnits="userSpaceOnUse"><stop class="d0phtb81o"/><stop class="d0phtb81o"/><stop offset="1" class="hwvatcc-y"/></radialGradient><radialGradient id="iuu4j9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.11941 -1.8243 6.0381 -.39524 8.366 24.787)" gradientUnits="userSpaceOnUse"><stop offset=".584" class="ie8_agh2b"/><stop offset="1" class="gzc_qccoq"/></radialGradient><radialGradient id="it74J4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.64063 -.01563 .00576 .60488 6.07 23.709)" gradientUnits="userSpaceOnUse"><stop class="u9mcm6llv"/><stop offset="1" class="b-3vnvcpj"/></radialGradient><radialGradient id="ibx1NPr" cx="0" cy="0" r="1" gradientTransform="matrix(1.01563 .01563 -.03485 2.26557 5.557 23.943)" gradientUnits="userSpaceOnUse"><stop class="ihz8r9bpq"/><stop offset="1" class="cabiwub4i"/></radialGradient><radialGradient id="iGvzzKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.80087 -.53995 .5353 -.79397 15.588 16.7)" gradientUnits="userSpaceOnUse"><stop class="id6hb3b7i"/><stop offset="1" class="nbyzmw_ck"/></radialGradient><radialGradient id="iFNUxrd" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 -.33594 .30415 .24757 15.494 16.404)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="z1-difb5b"/><stop offset="1" class="yxnjz7r7g"/></radialGradient><radialGradient id="iesb7eb" cx="0" cy="0" r="1" gradientTransform="matrix(.18962 -.81468 .57531 .1339 14.418 16.851)" gradientUnits="userSpaceOnUse"><stop class="mcd03_b4y"/><stop offset="1" class="e14bc-vgp"/></radialGradient><radialGradient id="iu9NI8d" cx="0" cy="0" r="1" gradientTransform="rotate(65.376 -3.82 19.263)scale(.41251)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="ipohnfkvg"/><stop offset="1" class="aur13kbnc"/></radialGradient><radialGradient id="i5U0f5c" cx="0" cy="0" r="1" gradientTransform="matrix(.41406 -.125 .14254 .47215 14.744 15.076)" gradientUnits="userSpaceOnUse"><stop class="clzavdftr"/><stop offset="1" class="w07b1tb5i"/></radialGradient><radialGradient id="ii4ZWCV" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 -.28126 .36059 .90144 10.98 25.944)" gradientUnits="userSpaceOnUse"><stop class="b9iguid0k"/><stop offset="1" class="rfxr5lvvz"/></radialGradient><radialGradient id="iHZFVsa" cx="0" cy="0" r="1" gradientTransform="rotate(-90.544 16.175 -7.897)scale(1.19329 .67738)" gradientUnits="userSpaceOnUse"><stop class="bcaxkqjfb"/><stop offset="1" class="kh4so6bgt"/></radialGradient><radialGradient id="i7skBKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.16406 -2.98016 0 18.6 20.85)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="yu1mih4mu"/><stop offset="1" class="eu5aevb0y"/></radialGradient><radialGradient id="iEzlkwc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.36328 -3.72499 0 18.6 21.377)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="cvn34-xwu"/><stop offset=".771" class="i8rkxoa5u"/></radialGradient><radialGradient id="iaUoEhd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.10465 .77326 -.66363 -.94804 24.784 9.063)" gradientUnits="userSpaceOnUse"><stop class="t_w7gbbck"/><stop offset="1" class="pbwt4gb4m"/></radialGradient><radialGradient id="ioygFpd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0138 .77326 -2.388 -.04264 22.147 16.312)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="seor_02fd"/><stop offset="1" class="cfhwg-9zy"/></radialGradient><radialGradient id="i0XmlAe" cx="0" cy="0" r="1" gradientTransform="matrix(.64844 -.00781 .01612 1.33804 17.065 15.568)" gradientUnits="userSpaceOnUse"><stop offset=".032" class="etx6bbf-f"/><stop offset="1" class="xbtn5acgm"/></radialGradient><radialGradient id="ian8Fob" cx="0" cy="0" r="1" gradientTransform="matrix(1.71874 -1.8125 1.7735 1.68175 12.166 29.272)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="i8ZeH5b" cx="0" cy="0" r="1" gradientTransform="rotate(-49.87 37.315 .956)scale(1.46152 1.87048)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="i2izg2d" cx="0" cy="0" r="1" gradientTransform="rotate(-49.87 43.143 -11.58)scale(1.46152 1.87048)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="i2LyDpd" cx="0" cy="0" r="1" gradientTransform="rotate(-133.238 18.9 9.256)scale(2.87398 2.81213)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="bu0v-9rgl"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="inK3Tfd" cx="0" cy="0" r="1" gradientTransform="matrix(-.625 3.92187 -.8118 -.12937 22.744 22.818)" gradientUnits="userSpaceOnUse"><stop class="th1brvxrz"/><stop offset="1" class="ux0of3-jj"/></radialGradient><radialGradient id="ieUWuOc" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 -1.89062 2.41965 2.03971 18.198 28.084)" gradientUnits="userSpaceOnUse"><stop offset=".233" class="b3dj2bied"/><stop offset="1" class="ma5b9zegf"/></radialGradient><radialGradient id="icOtgab" cx="0" cy="0" r="1" gradientTransform="matrix(.13544 1.98754 -.87055 .05932 21.16 12.508)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="tr08sbvmm"/><stop offset="1" class="fz8d0bv0m"/></radialGradient><radialGradient id="itJzvmd" cx="0" cy="0" r="1" gradientTransform="matrix(.27784 .32996 -1.10753 .9326 17.295 5.81)" gradientUnits="userSpaceOnUse"><stop offset=".005" class="de7oo9b3j"/><stop offset=".684" class="plvhkpbev"/></radialGradient><radialGradient id="iIa0KiN" cx="0" cy="0" r="1" gradientTransform="matrix(-.76846 -.12283 .14975 -.93689 20.587 5.727)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="ipXcT1c" cx="0" cy="0" r="1" gradientTransform="matrix(.49097 -4.75185 1.84635 .19077 17.822 6.54)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="iVJBCJg" cx="0" cy="0" r="1" gradientTransform="matrix(-.03697 .35782 -.55803 -.05766 18.688 5.574)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="iC9hQYW" cx="0" cy="0" r="1" gradientTransform="rotate(143.625 10.722 5.357)scale(4.27816 4.85116)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="jve2rcqoj"/><stop offset="1" class="kpbiulbbs"/></radialGradient><radialGradient id="ivRQBrb" cx="0" cy="0" r="1" gradientTransform="rotate(143.625 10.722 5.357)scale(4.27816 4.85116)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="sd2k4tbbl"/><stop offset="1" class="n3xu87-4f"/></radialGradient><radialGradient id="iA860hc" cx="0" cy="0" r="1" gradientTransform="matrix(.10748 2.49477 -1.1021 .04748 22.364 3.988)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="qvi3m-3ib"/><stop offset="1" class="sx_wpgngv"/></radialGradient><radialGradient id="ism8bYK" cx="0" cy="0" r="1" gradientTransform="matrix(1.3829 .05609 -.11007 2.71379 17.622 3.373)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ehlb6fbrs"/><stop offset="1" class="xv-sacbws"/></radialGradient><radialGradient id="iqTdpke" cx="0" cy="0" r="1" gradientTransform="matrix(.68551 -.12446 .06075 .33459 20.261 5.432)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="ihXGu4M" cx="0" cy="0" r="1" gradientTransform="matrix(.09533 1.10205 -1.1484 .09934 20.318 5.16)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="idKlvqd" cx="0" cy="0" r="1" gradientTransform="matrix(.25047 .02588 -.05028 .48664 18.284 5.405)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iMhZRfd" cx="0" cy="0" r="1" gradientTransform="matrix(.229 .02366 -.0512 .49558 18.128 5.409)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="itoCska" cx="0" cy="0" r="1" gradientTransform="matrix(.61594 -3.1794 1.00389 .19448 22.564 5.935)" gradientUnits="userSpaceOnUse"><stop class="fndizab4b"/><stop offset="1" class="hw8l16bxs"/></radialGradient><radialGradient id="imR7Pte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 .875 -1.0205 -1.3485 25.698 3.6)" gradientUnits="userSpaceOnUse"><stop class="v4yb5cu8i"/><stop offset="1" class="ewip82vxi"/></radialGradient><radialGradient id="i1sO2rd" cx="0" cy="0" r="1" gradientTransform="matrix(.14062 1.03125 -3.76156 .51293 23.823 2.74)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="i00c46bgu"/><stop offset="1" class="gb6cd3sju"/></radialGradient><radialGradient id="ieFIG9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.09701 1.94052 -1.12239 -.05611 21.205 9.62)" gradientUnits="userSpaceOnUse"><stop class="axeyyr5nz"/><stop offset="1" class="wq290abaa"/></radialGradient><radialGradient id="ixe3STk" cx="0" cy="0" r="1" gradientTransform="matrix(1.99028 .19405 -1.0368 10.63398 19.692 11.289)" gradientUnits="userSpaceOnUse"><stop offset=".516" class="rnfgp6bsq"/><stop offset="1" class="sjqhriwca"/></radialGradient><linearGradient id="ii7timF" x1="19.12" x2="19.349" y1="9.298" y2="9.294" gradientUnits="userSpaceOnUse"><stop class="b3gb996av"/><stop offset="1" class="crjyhppor"/></linearGradient><linearGradient id="io9N2mb" x1="21.963" x2="17.554" y1="16.662" y2="12.1" gradientUnits="userSpaceOnUse"><stop class="hjg9lybhz"/><stop offset="1" class="arwl47bdv"/></linearGradient><linearGradient id="ixgkPDc" x1="17.96" x2="9.835" y1="16.818" y2="24.131" gradientUnits="userSpaceOnUse"><stop class="scqcqwblc"/><stop offset="1" class="j5-6p70xh"/></linearGradient><linearGradient id="ik1Ynre" x1="10.312" x2="9.132" y1="25.295" y2="24.678" gradientUnits="userSpaceOnUse"><stop class="wjw662jrg"/><stop offset="1" class="xkzs54_ul"/></linearGradient><linearGradient id="iTlw1ze" x1="14.822" x2="15.422" y1="15.622" y2="15.622" gradientUnits="userSpaceOnUse"><stop class="p8hc-w2ji"/><stop offset=".573" class="c76owwbvh"/></linearGradient><linearGradient id="i8EtACb" x1="24.658" x2="24.187" y1="26.99" y2="26.646" gradientUnits="userSpaceOnUse"><stop offset=".323" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="iaibdoc" x1="12.588" x2="13.049" y1="26.982" y2="26.732" gradientUnits="userSpaceOnUse"><stop offset=".385" class="lzxtmdbfr"/><stop offset="1" class="ajt-21bdu"/></linearGradient><linearGradient id="i13oEde" x1="6.252" x2="11.604" y1="24.162" y2="26.435" gradientUnits="userSpaceOnUse"><stop class="bq9mpqbzy"/><stop offset="1" class="ka6kobc6f"/></linearGradient><linearGradient id="iGAFQ0c" x1="11.494" x2="14.151" y1="26.568" y2="24.662" gradientUnits="userSpaceOnUse"><stop class="f6z4yi_ag"/><stop offset="1" class="cu9n-vbgf"/></linearGradient><linearGradient id="iqA0X9a" x1="12.791" x2="12.963" y1="24.193" y2="24.662" gradientUnits="userSpaceOnUse"><stop class="ybejupycn"/><stop offset="1" class="o7v7nujms"/></linearGradient><linearGradient id="i2HwWcd" x1="24.776" x2="24.276" y1="24.162" y2="25.062" gradientUnits="userSpaceOnUse"><stop class="hlkhhwb3q"/><stop offset="1" class="b37qgpujw"/></linearGradient><linearGradient id="ib3lOhc" x1="15.219" x2="15.219" y1="16.769" y2="17.429" gradientUnits="userSpaceOnUse"><stop offset=".077" class="y05dlfbsr"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="iRqT9Id" x1="13.945" x2="15.024" y1="17.882" y2="17.882" gradientUnits="userSpaceOnUse"><stop offset=".326" class="mykl6fbtk"/><stop offset="1" class="uevlegbhj"/></linearGradient><linearGradient id="i2Fsfdc" x1="16.493" x2="15.675" y1="18.088" y2="18.088" gradientUnits="userSpaceOnUse"><stop class="jsdt5e8xl"/><stop offset="1" class="erpm-ebho"/></linearGradient><linearGradient id="iFjT9qd" x1="16.493" x2="16.206" y1="18.088" y2="18.088" gradientUnits="userSpaceOnUse"><stop class="gxhbeh9zc"/><stop offset="1" class="t07ov5bcy"/></linearGradient><linearGradient id="irp4HHd" x1="13.945" x2="14.236" y1="17.831" y2="17.831" gradientUnits="userSpaceOnUse"><stop class="xs80ogben"/><stop offset="1" class="snka5sm3m"/></linearGradient><linearGradient id="iu56Nre" x1="23.911" x2="23.901" y1="7.042" y2="8.247" gradientUnits="userSpaceOnUse"><stop class="ronnvab4v"/><stop offset="1" class="dt2-hrbth"/></linearGradient><linearGradient id="iYObvFc" x1="23.928" x2="22.216" y1="17.32" y2="17.155" gradientUnits="userSpaceOnUse"><stop offset=".357" class="ejmms-frd"/><stop offset="1" class="bd5h7cqqn"/></linearGradient><linearGradient id="i9OL0oc" x1="18.651" x2="18.651" y1="18.318" y2="19.318" gradientUnits="userSpaceOnUse"><stop offset=".219" class="jqu95-b8t"/><stop offset="1" class="vt606lu7d"/></linearGradient><linearGradient id="iYpPigb" x1="24.573" x2="23.276" y1="19.508" y2="19.508" gradientUnits="userSpaceOnUse"><stop class="e9_lu_tkl"/><stop offset="1" class="ms0rob30e"/></linearGradient><linearGradient id="ifYqZAe" x1="12.729" x2="13.244" y1="19.639" y2="19.639" gradientUnits="userSpaceOnUse"><stop offset=".255" class="aafld1b5m"/><stop offset="1" class="t9qy5zbtq"/></linearGradient><linearGradient id="iLslrTU" x1="20.565" x2="20.565" y1="15.008" y2="16.476" gradientUnits="userSpaceOnUse"><stop offset=".116" class="k8klmcqbt"/><stop offset="1" class="t8rqipb-o"/></linearGradient><linearGradient id="ihvlZNe" x1="18.588" x2="18.588" y1="21.896" y2="27.693" gradientUnits="userSpaceOnUse"><stop class="ebki_vbdj"/><stop offset=".752" class="w_fjow9gn"/></linearGradient><linearGradient id="iWtYetd" x1="14.244" x2="15.244" y1="25.537" y2="25.443" gradientUnits="userSpaceOnUse"><stop class="golah4bmm"/><stop offset="1" class="nhtvs4bus"/></linearGradient><linearGradient id="iVNc7pd" x1="20.205" x2="17.023" y1="25.702" y2="28.838" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="iRUjcEb" x1="25.351" x2="23.553" y1="27.512" y2="29.284" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset=".37" class="hxfvufi0i"/><stop offset=".778" class="hxfvufi0i"/><stop offset="1" class="bqaby2bzq"/></linearGradient><linearGradient id="iiFsHjb" x1="11.501" x2="12.985" y1="28.896" y2="27.459" gradientUnits="userSpaceOnUse"><stop class="bqaby2bzq"/><stop offset="1" class="hxfvufi0i"/></linearGradient><linearGradient id="iSpq6je" x1="20.231" x2="17.593" y1="6.377" y2="6.264" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="i1WU6Id" x1="20.205" x2="20.34" y1="5.49" y2="5.515" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="iIjUXWd" x1="18.155" x2="18.326" y1="5.057" y2="5.113" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iexsjSd" x1="25.573" x2="24.369" y1="6.006" y2="5.771" gradientUnits="userSpaceOnUse"><stop class="sputfhdoz"/><stop offset="1" class="x91xhsboa"/></linearGradient><linearGradient id="ik3z59u" x1="23.807" x2="23.994" y1="7.093" y2="5.818" gradientUnits="userSpaceOnUse"><stop class="zeqefbvfd"/><stop offset="1" class="aetcf802l"/></linearGradient><linearGradient id="ix29NMe" x1="10.023" x2="14.773" y1="23.037" y2="14.631" gradientUnits="userSpaceOnUse"><stop offset=".047" class="x9-imyafb"/><stop offset="1" class="uu4nvia_s"/></linearGradient><linearGradient id="iLkAOCe" x1="19.33" x2="19.963" y1="11.968" y2="11.968" gradientUnits="userSpaceOnUse"><stop class="o5h0oebxj"/><stop offset="1" class="ts_kmdhif"/></linearGradient><filter id="ijJfCFe" width="15.582" height="10.819" x="5.713" y="14.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.223529 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="iWLMvOp" width="6.441" height="2.956" x="5.508" y="23.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.133333 0 0 0 0 0.286275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.14902 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="iORB7fd" width="5.567" height="2.356" x="5.933" y="23.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_403" stdDeviation=".075"/></filter><filter id="i26SDUc" width="4.441" height="3.418" x="10.858" y="23.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.109804 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="iIZcOxe" width="4.535" height="3.468" x="21.807" y="23.228" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.145098 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="itQcZdc" width="4.718" height="10.273" x="20.506" y="8.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.145098 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="iPaVTkb" width="11.844" height="3.289" x="12.729" y="17.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.133333 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.184314 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="ioRAUhb" width="7.15" height="1.822" x="17.065" y="14.655" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.137255 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="iyidkWb" width="3.042" height="3.242" x="11.275" y="26.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="iEFEa8b" width="3.042" height="3.242" x="22.932" y="26.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="iXr3xdb" width=".953" height=".953" x="12.295" y="28.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="igEc5Gd" width=".953" height=".953" x="23.951" y="28.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="irCNqEd" width="9.072" height="5.925" x="14.052" y="21.896" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.0392157 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="i6OQ7mb" width="5.213" height="5.612" x="16.068" y="24.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.337255 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.494118 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="iLqUfjc" width="4.858" height="4.858" x="16.271" y="24.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_403" stdDeviation=".125"/></filter><filter id="ibhrQ1b" width="2.743" height="2.743" x="23.129" y="27.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_403" stdDeviation=".075"/></filter><filter id="iKetFwb" width="4.351" height="5.782" x="18.123" y="8.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_403" stdDeviation=".5"/></filter><filter id="iSJlK7c" width="2.743" height="2.743" x="11.4" y="27.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_403" stdDeviation=".075"/></filter><filter id="iXEm7bb" width="1.474" height="1.474" x="17.863" y="26.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.203922 0 0 0 0 0.294118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.247059 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="iNH6WBd" width="7.234" height="2.726" x="14.177" y="12.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.423529 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="i9Mkn7c" width="7.434" height="2.726" x="14.177" y="12.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.678431 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.537255 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="iowhDCe" width="1.884" height="1.437" x="13.714" y="13.588" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.623529 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="ikveJ4Y" width="1.948" height="1.321" x="14.102" y="13.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.623529 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="ikJp7Pb" width="4.309" height="4.933" x="17.389" y="3.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.596078 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="iDdPJUc" width="5.82" height="5.339" x="17.266" y="1.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.592157 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="ietkBkd" width="5.82" height="5.339" x="17.266" y="1.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.262745 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.054902 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_403" result="effect2_innerShadow_4002_403"/></filter><filter id="iNCsnOe" width="1.051" height=".694" x="18.085" y="4.154" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_403"/></filter><filter id="iYrVKVb" width="5.063" height="8.469" x="9.179" y="15.412" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_403" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-in-motorized-wheelchair-light" /></template>
<style>
.a0cytj3vs {
  stop-color: var(--svg-color--d49c8a, #D49C8A);
  stop-opacity: 0;
}

.aafld1b5m {
  stop-color: var(--svg-color--64576e, #64576E);
}

.aapalwo8e {
  d: path("M16.182 20.74h4.836v1.273h-4.836z");
}

.aetcf802l {
  stop-color: var(--svg-color--492f60, #492F60);
  stop-opacity: 0;
}

.ajt-21bdu {
  stop-color: var(--svg-color--3a183a, #3A183A);
}

.arwl47bdv {
  stop-color: var(--svg-color--142c6c, #142C6C);
  stop-opacity: 0;
}

.aur13kbnc {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
  stop-opacity: 0;
}

.axeyyr5nz {
  stop-color: var(--svg-color--44a1e7, #44A1E7);
}

.b-3vnvcpj {
  stop-color: var(--svg-color--565476, #565476);
  stop-opacity: 0;
}

.b10rjxgth {
  stop-color: var(--svg-color--f5c1ab, #F5C1AB);
}

.b11h0-bme {
  d: path("m14.487 26.645l-.426-3.4a1.2 1.2 0 0 1 1.191-1.349h6.672a1.2 1.2 0 0 1 1.191 1.343l-.406 3.4a1 1 0 0 1-.993.882H15.48a1 1 0 0 1-.992-.876");
}

.b15132bnl {
  cx: 22.508px;
  cy: 15.684px;
  r: 0.475px;
  fill: var(--svg-color--3e3a4a, #3E3A4A);
}

.b37qgpujw {
  stop-color: var(--svg-color--f24147, #F24147);
  stop-opacity: 0;
}

.b3dj2bied {
  stop-color: var(--svg-color--c7b9d7, #C7B9D7);
}

.b3gb996av {
  stop-color: var(--svg-color--ecac9a, #ECAC9A);
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.b9iguid0k {
  stop-color: var(--svg-color--cc3437, #CC3437);
}

.bcaxkqjfb {
  stop-color: var(--svg-color--404047, #404047);
}

.bd5h7cqqn {
  stop-color: var(--svg-color--5a4a6a, #5A4A6A);
  stop-opacity: 0;
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bq9mpqbzy {
  stop-color: var(--svg-color--474652, #474652);
}

.bqaby2bzq {
  stop-color: var(--svg-color--a09aa7, #A09AA7);
}

.bu0v-9rgl {
  stop-color: var(--svg-color--776287, #776287);
  stop-opacity: 0;
}

.butdkhblz {
  fill: var(--svg-color--4c477e, #4C477E);
  d: path("M10.53 24.262c-.196.485-.388.943-.567 1.346c-1.097-.411-4-1.833-4-1.833c.02-.163.217-.526.848-.677c.63-.15 2.033-.131 2.655-.103c0-.006.48.55 1.065 1.267");
}

.bvncjee1j {
  fill: var(--svg-color--55426a, #55426A);
  d: path("M22.883 3.888a1.2 1.2 0 0 1 1.39-.972l.565.1a1.2 1.2 0 0 1 .973 1.39l-.3 1.696a1.2 1.2 0 0 1-1.392.972l-.564-.1a1.2 1.2 0 0 1-.973-1.39z");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c76owwbvh {
  stop-color: var(--svg-color--393640, #393640);
}

.cabiwub4i {
  stop-color: var(--svg-color--535154, #535154);
  stop-opacity: 0;
}

.cfhwg-9zy {
  stop-color: var(--svg-color--422d5a, #422D5A);
  stop-opacity: 0;
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.clzavdftr {
  stop-color: var(--svg-color--5e4e70, #5E4E70);
}

.crgxtfbyy {
  cx: 12.771px;
  cy: 28.51px;
  r: 1.496px;
  fill: var(--svg-color--857d8e, #857D8E);
}

.crjyhppor {
  stop-color: var(--svg-color--ecac9a, #ECAC9A);
  stop-opacity: 0;
}

.cu9n-vbgf {
  stop-color: var(--svg-color--c7262d, #C7262D);
}

.cuar4pu2m {
  d: path("m19.466 12.928l.062-.5a5.2 5.2 0 0 1 1.883.265c-.01.164-.05.597-.125 1.016c-.094.523-.367 1.184-1.633 1.23c-1.265.047-3.468-.152-3.726-.222a2 2 0 0 0-.531-.063l-.97-.554c-.194.07-.374-.188-.132-.391c.325-.281.98-.326 1.266-.313c1.125-.387 3.073-.474 3.906-.468");
}

.cvn34-xwu {
  stop-color: var(--svg-color--832538, #832538);
  stop-opacity: 0;
}

.d06h_8buq {
  d: path("M14.924 15.115h.578V16.4h-.578z");
}

.d0phtb81o {
  stop-color: var(--svg-color--9d969d, #9D969D);
}

.d162jvikx {
  width: 11.844px;
  height: 2.839px;
  x: 12.729px;
  y: 18.089px;
  rx: 0.5px;
}

.d1q2qt76h {
  cx: 18.22px;
  cy: 5.092px;
  rx: 0.059px;
  ry: 0.08px;
}

.d9q4mwzxt {
  stop-color: var(--svg-color--5c5166, #5C5166);
}

.de7oo9b3j {
  stop-color: var(--svg-color--f9bfa6, #F9BFA6);
}

.dp41p39px {
  fill: var(--svg-color--e6b3a6, #E6B3A6);
  d: path("m19.466 12.928l.062-.5a5.2 5.2 0 0 1 1.883.265c-.01.164-.05.597-.125 1.016c-.094.523-.367 1.184-1.633 1.23c-1.265.047-3.468-.152-3.726-.222a2 2 0 0 0-.531-.063l-.97-.554c-.194.07-.374-.188-.132-.391c.325-.281.98-.326 1.266-.313c1.125-.387 3.073-.474 3.906-.468");
}

.dt2-hrbth {
  stop-color: var(--svg-color--2b2731, #2B2731);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.e14bc-vgp {
  stop-color: var(--svg-color--ab556a, #AB556A);
  stop-opacity: 0;
}

.e5nfrccvd {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.5 29.603a1.146 1.146 0 1 0 0-2.292a1.146 1.146 0 0 0 0 2.292Z");
}

.e9_lu_tkl {
  stop-color: var(--svg-color--685977, #685977);
}

.ebki_vbdj {
  stop-color: var(--svg-color--e4355d, #E4355D);
}

.ehlb6fbrs {
  stop-color: var(--svg-color--544b49, #544B49);
}

.eih5wcbly {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M18.6 30.006a2.531 2.531 0 1 0 0-5.063a2.531 2.531 0 0 0 0 5.063m0-1.02a1.512 1.512 0 1 0 0-3.024a1.512 1.512 0 0 0 0 3.024");
}

.ejmms-frd {
  stop-color: var(--svg-color--5a4a6a, #5A4A6A);
}

.entt9mbqv {
  cx: 12.771px;
  cy: 28.51px;
  r: 1.496px;
}

.erpm-ebho {
  stop-color: var(--svg-color--64597c, #64597C);
  stop-opacity: 0;
}

.etx6bbf-f {
  stop-color: var(--svg-color--6c5d7f, #6C5D7F);
}

.eu5aevb0y {
  stop-color: var(--svg-color--bb3143, #BB3143);
}

.ewip82vxi {
  stop-color: var(--svg-color--56426b, #56426B);
  stop-opacity: 0;
}

.f6z4yi_ag {
  stop-color: var(--svg-color--dd2f40, #DD2F40);
}

.fiobnycwk {
  d: path("m18.403 5.437l.011-.065c.018-.17-.04-.316-.13-.325c-.088-.009-.174.121-.192.291l-.003.067z");
}

.fndizab4b {
  stop-color: var(--svg-color--5e4a5e, #5E4A5E);
}

.ft5dv1b6b {
  fill: none;
}

.fz8d0bv0m {
  stop-color: var(--svg-color--f8c0b0, #F8C0B0);
  stop-opacity: 0;
}

.ga7b7ubfr {
  d: path("M21.96 9.287a1.4 1.4 0 0 1 1.382-1.172h.182a1.4 1.4 0 0 1 1.38 1.628l-1.378 8.346h-3.02z");
}

.gb6cd3sju {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
  stop-opacity: 0;
}

.golah4bmm {
  stop-color: var(--svg-color--db4459, #DB4459);
}

.gqx2wrbhf {
  d: path("M12.536 26.306h.471v1.492h-.471z");
}

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gxhbeh9zc {
  stop-color: var(--svg-color--483962, #483962);
}

.gzc_qccoq {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
}

.h2er9kbhc {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.772 29.603a1.146 1.146 0 1 0 0-2.292a1.146 1.146 0 0 0 0 2.292Z");
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.hdstylo5p {
  fill: var(--svg-color--f0303e, #F0303E);
  d: path("m25.92 25.147l-3.059-1.72l-1.054 3.269h3.714a.827.827 0 0 0 .399-1.549");
}

.hi-ljefvf {
  d: path("M17.065 15.505a.7.7 0 0 1 .7-.7h6.3l-.274 1.671h-6.026a.7.7 0 0 1-.7-.7z");
}

.hjg9lybhz {
  stop-color: var(--svg-color--142c6c, #142C6C);
}

.hlkhhwb3q {
  stop-color: var(--svg-color--f24147, #F24147);
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hw8l16bxs {
  stop-color: var(--svg-color--5e4a5e, #5E4A5E);
  stop-opacity: 0;
}

.hwvatcc-y {
  stop-color: var(--svg-color--9d969d, #9D969D);
  stop-opacity: 0;
}

.hx49fyb4j {
  cx: 12.771px;
  cy: 28.51px;
  r: 0.377px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.hxfvufi0i {
  stop-color: var(--svg-color--a09aa7, #A09AA7);
  stop-opacity: 0;
}

.i00c46bgu {
  stop-color: var(--svg-color--4b3c57, #4B3C57);
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.i8rkxoa5u {
  stop-color: var(--svg-color--832538, #832538);
}

.ibdgujbbi {
  fill-rule: evenodd;
  d: path("M5.697 23.848a.375.375 0 0 1 .502-.17l3.788 1.864l.01.003h1.427a.375.375 0 0 1 0 .75H9.998a.8.8 0 0 1-.343-.08L5.868 24.35a.375.375 0 0 1-.17-.502");
}

.id6hb3b7i {
  stop-color: var(--svg-color--b11943, #B11943);
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.ie8_agh2b {
  stop-color: var(--svg-color--3e3e6c, #3E3E6C);
  stop-opacity: 0;
}

.ifgvwhkxh {
  d: path("m20.04 6.218l.319-1.3a.67.67 0 0 1-.32 1.3");
}

.ihz8r9bpq {
  stop-color: var(--svg-color--535154, #535154);
}

.ipohnfkvg {
  stop-color: var(--svg-color--5a4a71, #5A4A71);
}

.j0xqyhb3r {
  stop-color: var(--svg-color--5382a1, #5382A1);
}

.j5-6p70xh {
  stop-color: var(--svg-color--908893, #908893);
}

.j6tziiblj {
  width: 11.844px;
  height: 2.839px;
  x: 12.729px;
  y: 18.089px;
  fill: var(--svg-color--58426f, #58426F);
  rx: 0.5px;
}

.jiurw55ug {
  fill: var(--svg-color--3b3349, #3B3349);
  fill-rule: evenodd;
  d: path("M5.697 23.848a.375.375 0 0 1 .502-.17l3.788 1.864l.01.003h1.427a.375.375 0 0 1 0 .75H9.998a.8.8 0 0 1-.343-.08L5.868 24.35a.375.375 0 0 1-.17-.502");
}

.jqu95-b8t {
  stop-color: var(--svg-color--574568, #574568);
}

.jsdt5e8xl {
  stop-color: var(--svg-color--64597c, #64597C);
}

.jve2rcqoj {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
}

.jzl720bvd {
  stop-color: var(--svg-color--816d8d, #816D8D);
}

.k8klmcqbt {
  stop-color: var(--svg-color--645381, #645381);
}

.ka6kobc6f {
  stop-color: var(--svg-color--474652, #474652);
  stop-opacity: 0;
}

.kc35rj-oq {
  d: path("m12.85 15.518l3.914-.48l4.53 3.427h-8.582s-1.636 4.633-2.75 7.143c-1.096-.411-4-1.833-4-1.833c.02-.163.218-.526.849-.677c.63-.15 2.033-.131 2.655-.102c.117-.826.439-2.957.788-4.883c.35-1.925 1.876-2.532 2.595-2.595");
}

.kegmapbvr {
  stop-color: var(--svg-color--5c5166, #5C5166);
  stop-opacity: 0;
}

.kh4so6bgt {
  stop-color: var(--svg-color--404047, #404047);
  stop-opacity: 0;
}

.kpbiulbbs {
  stop-color: var(--svg-color--ffa629, #FFA629);
}

.kwf7z6buh {
  cx: 15.212px;
  cy: 14.805px;
  r: 0.518px;
  fill: var(--svg-color--4a2a60, #4A2A60);
}

.kx0-osb2n {
  fill: var(--svg-color--5e4f7f, #5E4F7F);
  d: path("M13.945 17.27a.5.5 0 0 1 .5-.5h1.548a.5.5 0 0 1 .5.5v.819h-2.548z");
}

.l-ch5ci-p {
  stop-color: var(--svg-color--2d64a3, #2D64A3);
  stop-opacity: 0;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.ln49lacxs {
  d: path("m25.92 25.147l-3.059-1.72l-1.054 3.269h3.714a.827.827 0 0 0 .399-1.549");
}

.lnq-uwb2f {
  width: 0.619px;
  height: 2.008px;
  x: 23.613px;
  y: 6.61px;
  rx: 0.31px;
}

.lt84bikqe {
  d: path("M17.469 5.485a.9.9 0 0 0 .28-.394l.164.017l-.107 1.03c-.21.105-.489.057-.553-.14c-.055-.168.02-.363.216-.513");
}

.lzxtmdbfr {
  stop-color: var(--svg-color--4a3a4c, #4A3A4C);
}

.ma5b9zegf {
  stop-color: var(--svg-color--9c83b4, #9C83B4);
}

.mb7aovqiv {
  cx: 15.212px;
  cy: 14.805px;
  r: 0.518px;
}

.mcd03_b4y {
  stop-color: var(--svg-color--ab556a, #AB556A);
}

.mplkytb5s {
  cx: 24.428px;
  cy: 28.51px;
  r: 0.894px;
}

.ms0rob30e {
  stop-color: var(--svg-color--58426e, #58426E);
  stop-opacity: 0;
}

.mykl6fbtk {
  stop-color: var(--svg-color--564778, #564778);
}

.n3xu87-4f {
  stop-color: var(--svg-color--1d0d23, #1D0D23);
}

.n5si-vkmf {
  cx: 12.771px;
  cy: 28.51px;
  r: 0.894px;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nadkggbux {
  fill: var(--svg-color--857d8e, #857D8E);
  fill-rule: evenodd;
  d: path("M24.428 30.006a1.496 1.496 0 1 0 0-2.993a1.496 1.496 0 0 0 0 2.993m0-.603a.894.894 0 1 0 0-1.787a.894.894 0 0 0 0 1.787");
}

.nbyzmw_ck {
  stop-color: var(--svg-color--b52f5e, #B52F5E);
}

.nhtvs4bus {
  stop-color: var(--svg-color--db4459, #DB4459);
  stop-opacity: 0;
}

.nkpj6tq5u {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M18.804 4.698c-.121-.107-.313-.132-.44-.145a.2.2 0 1 1 .041-.398l.01.001c.117.012.43.044.654.243a.2.2 0 0 1-.265.3");
}

.nkqm-bcwx {
  d: path("m19.593 10.106l-.263 2.526c.688 0 1.692.101 2.07.172c.075-.523.233-1.725.274-2.356c.052-.788-.17-1.098-.424-1.267a1 1 0 0 0-1.083 0c-.39.24-.545.716-.574.925");
}

.nov_osbjm {
  stop-color: var(--svg-color--e19d8a, #E19D8A);
}

.o-40n7v3x {
  fill-rule: evenodd;
  d: path("M24.428 30.006a1.496 1.496 0 1 0 0-2.993a1.496 1.496 0 0 0 0 2.993m0-.603a.894.894 0 1 0 0-1.787a.894.894 0 0 0 0 1.787");
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.o5h0oebxj {
  stop-color: var(--svg-color--478ece, #478ECE);
}

.o7v7nujms {
  stop-color: var(--svg-color--b92c31, #B92C31);
  stop-opacity: 0;
}

.o9_83db5k {
  d: path("M10.53 24.262c-.196.485-.388.943-.567 1.346c-1.097-.411-4-1.833-4-1.833c.02-.163.217-.526.848-.677c.63-.15 2.033-.131 2.655-.103c0-.006.48.55 1.065 1.267");
}

.p6_urry8d {
  d: path("M19.123 6.95h1.914v2.752h-1.914z");
}

.p6c0fhbrq {
  d: path("M17.77 4.79c.112-.73.386-1.06.509-1.152l3.419.354l-.242 2.903c-.995 1.862-3.427 1.695-3.716.955s-.098-2.215.03-3.06");
}

.p8hc-w2ji {
  stop-color: var(--svg-color--746e6d, #746E6D);
}

.pbwt4gb4m {
  stop-color: var(--svg-color--675876, #675876);
  stop-opacity: 0;
}

.plvhkpbev {
  stop-color: var(--svg-color--e29f90, #E29F90);
}

.ppt-j6bdy {
  d: path("M18.583 5.456v-.004c.03-.293-.07-.544-.226-.56c-.155-.016-.305.209-.336.502v.004z");
}

.ptiqigyhx {
  d: path("M22.883 3.888a1.2 1.2 0 0 1 1.39-.972l.565.1a1.2 1.2 0 0 1 .973 1.39l-.3 1.696a1.2 1.2 0 0 1-1.392.972l-.564-.1a1.2 1.2 0 0 1-.973-1.39z");
}

.q40uu5bap {
  cx: 15.212px;
  cy: 16.701px;
  r: 0.794px;
}

.q9d0l_bnd {
  cx: 18.6px;
  cy: 27.474px;
  r: 1.512px;
}

.qvi3m-3ib {
  stop-color: var(--svg-color--464143, #464143);
}

.qzfsgzpkj {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.028 5.399l.905.093c.037-.358-.135-.67-.385-.696s-.483.244-.52.603");
}

.rfxr5lvvz {
  stop-color: var(--svg-color--cc3437, #CC3437);
  stop-opacity: 0;
}

.ri8idabqv {
  d: path("M24.187 26.306h.471v1.492h-.471z");
}

.rnfgp6bsq {
  stop-color: var(--svg-color--1e6db7, #1E6DB7);
  stop-opacity: 0;
}

.ronnvab4v {
  stop-color: var(--svg-color--211b2c, #211B2C);
}

.rva11cbyn {
  cx: 24.428px;
  cy: 28.51px;
  r: 0.377px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.s--8ht3bv {
  fill: var(--svg-color--ffc136, #FFC136);
  d: path("m19.466 12.928l.062-.5a5.2 5.2 0 0 1 1.883.265c-.01.164-.05.597-.125 1.016c-.094.523-.367 1.184-1.633 1.23c-1.265.047-3.468-.152-3.726-.222a2 2 0 0 0-.531-.063l-.97-.554c-.194.07-.374-.188-.132-.391c.325-.281.98-.326 1.266-.313c1.125-.387 3.073-.474 3.906-.468");
}

.scqcqwblc {
  stop-color: var(--svg-color--7d7172, #7D7172);
}

.sd2k4tbbl {
  stop-color: var(--svg-color--251a23, #251A23);
}

.seor_02fd {
  stop-color: var(--svg-color--422d5a, #422D5A);
}

.sgi6nwbff {
  fill: var(--svg-color--2c66a4, #2C66A4);
  d: path("m19.386 10.3l-.263 2.526c.688 0 1.692.102 2.07.172c.074-.522.233-1.725.274-2.355c.052-.788-.17-1.099-.424-1.268a1 1 0 0 0-1.083 0c-.39.24-.546.717-.574.925");
}

.sjqhriwca {
  stop-color: var(--svg-color--023981, #023981);
}

.snka5sm3m {
  stop-color: var(--svg-color--6b6080, #6B6080);
  stop-opacity: 0;
}

.sputfhdoz {
  stop-color: var(--svg-color--6a5c77, #6A5C77);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.sx_wpgngv {
  stop-color: var(--svg-color--464143, #464143);
  stop-opacity: 0;
}

.t_w7gbbck {
  stop-color: var(--svg-color--675876, #675876);
}

.t07ov5bcy {
  stop-color: var(--svg-color--483962, #483962);
  stop-opacity: 0;
}

.t8rqipb-o {
  stop-color: var(--svg-color--523579, #523579);
}

.t9qy5zbtq {
  stop-color: var(--svg-color--64576e, #64576E);
  stop-opacity: 0;
}

.th1brvxrz {
  stop-color: var(--svg-color--ed516c, #ED516C);
}

.tittjnbcr {
  d: path("M18.403 4.005c-.6-.062-.852-.431-.837-.86c.063-.601.535-.682.715-.682c.202-.001.283-.014.583-.182a.83.83 0 0 1 .843-.004c.129.079.426.142.648.1c.368-.07.647-.038.9.202c.177.166.318.18.547.204c.315.033.568.201.754.375c.555.517.324 2.076-.064 2.926c-.371.813-.81.867-1.164.798c-.426-.083-.502-.42-.539-.7a52 52 0 0 0-.145-.976a.98.98 0 0 1-.423-.666c-.055-.364-.41-.442-.655-.444c-.15 0-.561-.029-1.163-.09");
}

.tnmhci3wx {
  fill: var(--svg-color--dda89d, #DDA89D);
  d: path("M14.164 14.767c.417-.495.92-.668 1.13-.707c.222-.062.651-.075.726.122a.43.43 0 0 1-.062.418a1.95 1.95 0 0 0-1.32.55a.32.32 0 0 1-.443.004a.284.284 0 0 1-.03-.387");
}

.tr08sbvmm {
  stop-color: var(--svg-color--f8c0b0, #F8C0B0);
}

.ts_kmdhif {
  stop-color: var(--svg-color--478ece, #478ECE);
  stop-opacity: 0;
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.u9mcm6llv {
  stop-color: var(--svg-color--565476, #565476);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uc2shjbgg {
  d: path("m11.28 25.147l3.058-1.72l.961 3.269h-3.62a.827.827 0 0 1-.4-1.549");
}

.ucj-rmbzy {
  d: path("m10.71 17.974l-1.031 5.079l.344.328l1.718-5.875h2v-1.594l-1.281.156c-1.125.125-1.636 1.323-1.75 1.906");
}

.uevlegbhj {
  stop-color: var(--svg-color--5b4874, #5B4874);
  stop-opacity: 0;
}

.uf2kifdvc {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M18.7 29.403a2.029 2.029 0 1 0 0-4.058a2.029 2.029 0 0 0 0 4.058Z");
}

.uu4nvia_s {
  stop-color: var(--svg-color--958d9a, #958D9A);
  stop-opacity: 0;
}

.ux0of3-jj {
  stop-color: var(--svg-color--e2305a, #E2305A);
  stop-opacity: 0;
}

.v4yb5cu8i {
  stop-color: var(--svg-color--695b77, #695B77);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vt606lu7d {
  stop-color: var(--svg-color--574568, #574568);
  stop-opacity: 0;
}

.w_fjow9gn {
  stop-color: var(--svg-color--d61f4c, #D61F4C);
}

.w07b1tb5i {
  stop-color: var(--svg-color--5e4e70, #5E4E70);
  stop-opacity: 0;
}

.w1w5tgb0x {
  fill: var(--svg-color--489ada, #489ADA);
  d: path("m16.73 15.013l3.792 3.118l1.44-8.172c-.196-1.362-1.875-1.576-2.518-1.507c-.642.068-1.37.437-1.875 1.978c-.405 1.234-.728 3.57-.84 4.583");
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.wjw662jrg {
  stop-color: var(--svg-color--321d4a, #321D4A);
}

.wnft2sbxi {
  fill: var(--svg-color--55416a, #55416A);
  d: path("M21.96 9.287a1.4 1.4 0 0 1 1.382-1.172h.182a1.4 1.4 0 0 1 1.38 1.628l-1.378 8.346h-3.02z");
}

.wq290abaa {
  stop-color: var(--svg-color--44a1e7, #44A1E7);
  stop-opacity: 0;
}

.x6jhwbjfz {
  fill: var(--svg-color--328ce0, #328CE0);
  d: path("m19.593 10.106l-.263 2.526c.688 0 1.692.101 2.07.172c.075-.523.233-1.725.274-2.356c.052-.788-.17-1.098-.424-1.267a1 1 0 0 0-1.083 0c-.39.24-.545.716-.574.925");
}

.x9-imyafb {
  stop-color: var(--svg-color--958d9a, #958D9A);
}

.x91xhsboa {
  stop-color: var(--svg-color--55426a, #55426A);
  stop-opacity: 0;
}

.xbtn5acgm {
  stop-color: var(--svg-color--6c5d7f, #6C5D7F);
  stop-opacity: 0;
}

.xkzs54_ul {
  stop-color: var(--svg-color--4d487f, #4D487F);
  stop-opacity: 0;
}

.xs80ogben {
  stop-color: var(--svg-color--6b6080, #6B6080);
}

.xv-sacbws {
  stop-color: var(--svg-color--544b49, #544B49);
  stop-opacity: 0;
}

.xz-6k3bpg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m6.158 24.014l3.89 1.906h1.227");
}

.y05dlfbsr {
  stop-color: var(--svg-color--5b4874, #5B4874);
}

.y1f7q6bmk {
  fill: var(--svg-color--dda89d, #DDA89D);
  d: path("M13.761 14.576c.367-.533.853-.754 1.057-.812c.215-.083.641-.137.735.051a.43.43 0 0 1-.023.422a1.95 1.95 0 0 0-1.261.675a.32.32 0 0 1-.44.047a.284.284 0 0 1-.068-.383");
}

.ybejupycn {
  stop-color: var(--svg-color--b92c31, #B92C31);
}

.yu1mih4mu {
  stop-color: var(--svg-color--9c1a55, #9C1A55);
}

.yxnjz7r7g {
  stop-color: var(--svg-color--c54169, #C54169);
  stop-opacity: 0;
}

.z-2ie6sne {
  stop-color: var(--svg-color--2d64a3, #2D64A3);
}

.z1-difb5b {
  stop-color: var(--svg-color--c54169, #C54169);
}

.z66hukbak {
  d: path("m16.73 15.013l3.792 3.118l1.44-8.172c-.196-1.362-1.875-1.576-2.518-1.507c-.642.068-1.37.437-1.875 1.978c-.405 1.234-.728 3.57-.84 4.583");
}

.zdh48sb9s {
  stop-color: var(--svg-color--816d8d, #816D8D);
  stop-opacity: 0;
}

.zeqefbvfd {
  stop-color: var(--svg-color--321c43, #321C43);
}

.zf01zc1zi {
  cx: 18.6px;
  cy: 27.474px;
  r: 0.637px;
  fill: var(--svg-color--3e384b, #3E384B);
}

.zqylsrrgt {
  stop-color: var(--svg-color--5382a1, #5382A1);
  stop-opacity: 0;
}

.zuv46pbeh {
  stop-color: var(--svg-color--d49c8a, #D49C8A);
}

.zw49qzbqk {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M18.606 6.49c.04.049.03.121-.019.161c-.24.192-.561.214-.663.214a.115.115 0 1 1 0-.23c.087 0 .342-.023.52-.164a.115.115 0 0 1 .162.018");
}

.zyodnlbru {
  d: path("M13.945 17.27a.5.5 0 0 1 .5-.5h1.548a.5.5 0 0 1 .5.5v.819h-2.548z");
}

</style>
