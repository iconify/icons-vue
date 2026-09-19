<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLmWXXc)"><path class="jhlh1_3ek"/><path fill="url(#ijJnbEe)" class="vb809lo-e"/></g><path fill="url(#i6qhIMe)" class="vb809lo-e"/><path fill="url(#iMX3qoe)" class="vb809lo-e"/><path fill="url(#iojSsLc)" class="vb809lo-e"/><path fill="url(#ioT8ldb)" class="vb809lo-e"/><g filter="url(#i6WHzqb)"><path class="siw2d1f7p"/><path fill="url(#izT5PGd)" class="i9-uutisp"/></g><path fill="url(#i4fAiPd)" class="xtp47zbsj"/><path fill="url(#ila6ipb)" class="xtp47zbsj"/><path fill="url(#iQuJ98d)" class="u--ocwryb"/><path fill="url(#iJ67Gde)" class="sazwi3bdn"/><path fill="url(#il6NAWb)" class="sazwi3bdn"/><g filter="url(#idTb8Ey)"><path fill="url(#inumkee)" class="qnmjgylyq"/><path fill="url(#ihJgNrc)" class="qnmjgylyq"/></g><g filter="url(#iq2kkke)"><circle fill="url(#iAisVdc)" class="s2ikxxbfc"/></g><g filter="url(#iP28t2d)"><circle fill="url(#iuX5Neb)" class="qv62lactv"/></g><g filter="url(#iMjOTyc)"><circle fill="url(#i9dRGae)" class="ae99og76i"/></g><rect fill="url(#iL1evwb)" transform="rotate(26.595 20.662 12.797)" class="i34rybopj"/><g filter="url(#ivvza9t)"><path fill="url(#imOxMfG)" class="pekg0u7cp"/></g><path class="zyhd--c_o"/><g filter="url(#iztH5ob)"><path class="drevzvb2z"/><path fill="url(#iTZSY5Q)" class="frgrxi9fy"/><path fill="url(#iUgFvud)" class="frgrxi9fy"/></g><g filter="url(#i7avOnH)"><path fill="url(#i792cHc)" class="gwjr899hs"/><path fill="url(#iM7HHze)" class="gwjr899hs"/><path fill="url(#iADJpWd)" class="gwjr899hs"/></g><path fill="url(#iRsy8Zd)" class="xt887yc-y"/><path fill="url(#iIYpcRf)" class="xt887yc-y"/><path clip-rule="evenodd" class="irvsablei"/><path fill="url(#iXPDkTd)" clip-rule="evenodd" class="l89w7ttua"/><path clip-rule="evenodd" class="tc7qg6b0q"/><path fill="url(#iDliI6e)" clip-rule="evenodd" class="x2d1t4xtf"/><path clip-rule="evenodd" class="ilhw8v5oy"/><path fill="url(#iLzwZBb)" clip-rule="evenodd" class="ljni-v35c"/><path clip-rule="evenodd" class="f9qkq2bgn"/><path fill="url(#iByEyEd)" clip-rule="evenodd" class="wc05b2bod"/><path class="qny9ytbij"/><path fill="url(#ibSxR4c)" class="uu4f6-byw"/><g filter="url(#iBTi4Ke)"><path fill="url(#iqofZec)" class="so3eyo06u"/></g><g filter="url(#ir7G3Vd)"><path fill="url(#iBybyQb)" class="olg-72bto"/></g><g filter="url(#iglMucn)"><path stroke="url(#iNeOQ4F)" class="on9u00bey"/></g><path fill="url(#iRPyP0N)" class="b5nd2m-sq"/><path fill="url(#iGfNsYc)" class="b5nd2m-sq"/><path fill="url(#iR8hEDr)" class="a4fvj8bnp"/><path fill="url(#izQ4Euc)" class="a4fvj8bnp"/><path fill="url(#idLIGeG)" class="wnm4h6zib"/><path fill="url(#iIGnFXh)" class="wnm4h6zib"/><path fill="url(#iTmhele)" class="wnm4h6zib"/><path fill="url(#iUutNOd)" class="wnm4h6zib"/><path fill="url(#ifNQpnb)" class="wnm4h6zib"/><g filter="url(#inoILHb)"><path class="y3p74o-xo"/></g><g filter="url(#iOBjfUs)"><path fill="url(#i3w5fge)" class="or_7yib9u"/><path fill="url(#ia4oiEd)" class="or_7yib9u"/><path fill="url(#i7ZK5yd)" class="or_7yib9u"/><path fill="url(#i29E4Qd)" class="or_7yib9u"/></g><g filter="url(#irkR4kb)"><path stroke="url(#izZf3cq)" class="c9oouybqp"/></g><path fill="url(#iK62urc)" class="f30_2gbsx"/><g filter="url(#ijGJctV)"><path fill="url(#iAF1lPc)" class="bg90e8h8i"/><path fill="url(#iMz9WKd)" class="bg90e8h8i"/><path fill="url(#iJbOJTb)" class="bg90e8h8i"/><path fill="url(#iny6bTj)" class="bg90e8h8i"/><path fill="url(#i4VKWMc)" class="bg90e8h8i"/></g><g filter="url(#iL5Dwne)"><path class="ge106kfvz"/></g><g filter="url(#izSurbe)"><path class="npu64rzpx"/></g><g filter="url(#i2eQjab)"><path fill="url(#iRphd5b)" class="y6c1p2x8v"/><path fill="url(#inDYtLc)" class="y6c1p2x8v"/></g><g filter="url(#izjHAFb)"><path fill="url(#i4u9CsE)" class="kr_erp7zc"/><path fill="url(#iYj0jgg)" class="kr_erp7zc"/><path fill="url(#iOrNJkc)" class="kr_erp7zc"/><path fill="url(#ijuERJb)" class="kr_erp7zc"/><path fill="url(#iYjzgcF)" class="kr_erp7zc"/></g><path class="rw5mc4bto"/><path fill="url(#ibaPN6w)" class="nhjaj61fi"/><path class="azfgivboh"/><g filter="url(#i21q0yc)"><path class="brt5yycyj"/><path fill="url(#iSkYSgc)" class="l0w5k5oua"/></g><g filter="url(#iUINDSc)"><path fill="url(#iOqQqrh)" class="kjlqo_13i"/></g><path class="k-l9f-bpq"/><path fill="url(#iaWUpgb)" class="pmjfhr11v"/><path class="s6k9w6bfo"/><g filter="url(#iLluEou)"><path fill="url(#iAF0g9U)" class="d2m2xebio"/></g><g filter="url(#iefQKdR)"><ellipse transform="rotate(-27.914 13.095 5.707)" class="j5xpxuvyt"/><ellipse fill="url(#i0qp5Nd)" transform="rotate(-27.914 13.095 5.707)" class="dnlo8zm8l"/></g><path fill="url(#i5tvMkd)" class="gzlr_0cpw"/><path fill="url(#i5DzEEc)" class="gzlr_0cpw"/><path fill="url(#iq9Jumb)" class="gzlr_0cpw"/><path fill="url(#iiQaXwe)" class="b2f11iceb"/><path fill="url(#iYgPwTd)" class="b2f11iceb"/><g filter="url(#iIxFrQd)"><path class="pjme70zim"/></g><g filter="url(#iSgL88b)"><path class="itnwk0wzv"/></g><defs><radialGradient id="i6qhIMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.985 21.758)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="iojSsLc" cx="0" cy="0" r="1" gradientTransform="matrix(3.56253 -6.12498 3.8162 2.21965 22.203 21.914)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="ioT8ldb" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.758)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="izT5PGd" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.17 25.196)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="i4fAiPd" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.26562 1.6575 .2251 9.579 26.414)" gradientUnits="userSpaceOnUse"><stop class="jobbcdb5u"/><stop offset="1" class="ztrk-1hpr"/></radialGradient><radialGradient id="il6NAWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.46)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="ihJgNrc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.738 2.812)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="iAisVdc" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.217 11.132)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iuX5Neb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.544)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i9dRGae" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.17 9.166)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iL1evwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.096)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="l0ervjwrq"/><stop offset="1" class="h8-lgt47k"/></radialGradient><radialGradient id="imOxMfG" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.201 10.919)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="q-9x-2bzr"/><stop offset="1" class="doutuqf7h"/></radialGradient><radialGradient id="iTZSY5Q" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.928 6.711)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="yt5sdf2gy"/><stop offset="1" class="n0_4eow9o"/></radialGradient><radialGradient id="iUgFvud" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.34 10.547)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="nf0740e8o"/><stop offset="1" class="fltjd-k8p"/></radialGradient><radialGradient id="iM7HHze" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.414)" gradientUnits="userSpaceOnUse"><stop class="qfyn005sz"/><stop offset="1" class="inzu6lb7s"/></radialGradient><radialGradient id="iADJpWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09375 -2.46875 0 13.766 8.227)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="fu31k5bmq"/><stop offset="1" class="zkqd2ycat"/></radialGradient><radialGradient id="iIYpcRf" cx="0" cy="0" r="1" gradientTransform="rotate(24.436 -15.497 48.342)scale(3.39814 2.30082)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="s41d30h-g"/><stop offset="1" class="woc0miqaj"/></radialGradient><radialGradient id="iXPDkTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.32031 -.9626 1.21082 -.4029 5.665 13.625)" gradientUnits="userSpaceOnUse"><stop offset=".081" class="bohes4bvb"/><stop offset="1" class="b8-5lhb5p"/></radialGradient><radialGradient id="iDliI6e" cx="0" cy="0" r="1" gradientTransform="matrix(-.25782 -.71094 1.29265 -.46878 5.649 14.039)" gradientUnits="userSpaceOnUse"><stop offset=".081" class="bohes4bvb"/><stop offset="1" class="b8-5lhb5p"/></radialGradient><radialGradient id="iLzwZBb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25403 -1.03125 1.96272 -.48347 5.747 14.82)" gradientUnits="userSpaceOnUse"><stop offset=".081" class="bohes4bvb"/><stop offset="1" class="b8-5lhb5p"/></radialGradient><radialGradient id="iByEyEd" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 -.59147 1.24454 -.57535 6.049 15.063)" gradientUnits="userSpaceOnUse"><stop offset=".081" class="bohes4bvb"/><stop offset="1" class="b8-5lhb5p"/></radialGradient><radialGradient id="ibSxR4c" cx="0" cy="0" r="1" gradientTransform="matrix(.42822 .95084 -2.90206 1.30698 6.517 14.508)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="b8-5lhb5p"/><stop offset="1" class="bohes4bvb"/></radialGradient><radialGradient id="iqofZec" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.51 15.396)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iRPyP0N" cx="0" cy="0" r="1" gradientTransform="matrix(-.38572 1.64855 -1.95834 -.4582 16.633 6.57)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="xitcw8bap"/><stop offset="1" class="by5wrxbms"/></radialGradient><radialGradient id="iGfNsYc" cx="0" cy="0" r="1" gradientTransform="rotate(53.902 1.574 19.376)scale(.22014 .18701)" gradientUnits="userSpaceOnUse"><stop class="ke8n9wjsm"/><stop offset="1" class="iav904f4q"/></radialGradient><radialGradient id="iR8hEDr" cx="0" cy="0" r="1" gradientTransform="matrix(.58944 1.73485 -.78857 .26793 11.726 6.622)" gradientUnits="userSpaceOnUse"><stop class="b9qaylb2c"/><stop offset="1" class="gz8haxb3i"/></radialGradient><radialGradient id="izQ4Euc" cx="0" cy="0" r="1" gradientTransform="rotate(72.29 1.479 11.537)scale(.46292 .40607)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="n8euy9vjg"/><stop offset=".977" class="z8auuww1t"/></radialGradient><radialGradient id="idLIGeG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31162 0 0 -4.08923 15.42 6.154)" gradientUnits="userSpaceOnUse"><stop class="wbf-2ib5u"/><stop offset="1" class="r2t9jab3e"/></radialGradient><radialGradient id="iIGnFXh" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.89313 7.36449 0 14.094 9.351)" gradientUnits="userSpaceOnUse"><stop offset=".082" class="bkz_cdc-o"/><stop offset=".759" class="yhtyhvpuw"/></radialGradient><radialGradient id="iTmhele" cx="0" cy="0" r="1" gradientTransform="matrix(-.178 2.6981 -.99194 -.06544 16.46 6.052)" gradientUnits="userSpaceOnUse"><stop offset=".39" class="swgfs-c3o"/><stop offset="1" class="lppsh4wvc"/></radialGradient><radialGradient id="iUutNOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.62517 .75267 0 13.255 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="u7o3559vd"/><stop offset="1" class="kbjuoc3rc"/></radialGradient><radialGradient id="ifNQpnb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.67884 .88048 0 15.28 5.45)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="bija72usz"/><stop offset="1" class="wwr7m_5oe"/></radialGradient><radialGradient id="izZf3cq" cx="0" cy="0" r="1" gradientTransform="matrix(.1535 -.2739 .79707 .4467 13.681 7.609)" gradientUnits="userSpaceOnUse"><stop class="ninpi-65y"/><stop offset="1" class="bjbw-ir7e"/></radialGradient><radialGradient id="iK62urc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.3187 1.28217 0 14.18 7.72)" gradientUnits="userSpaceOnUse"><stop class="g3hjbil2k"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iMz9WKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.52878 4.4805 0 11.867 5.455)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="ven54yrxx"/><stop offset="1" class="wrlksbcrj"/></radialGradient><radialGradient id="iJbOJTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.60626 2.84598 0 16.329 5.455)" gradientUnits="userSpaceOnUse"><stop class="hlw3e_blf"/><stop offset="1" class="wxscdbbqi"/></radialGradient><radialGradient id="iny6bTj" cx="0" cy="0" r="1" gradientTransform="rotate(-160.666 8.226 -.023)scale(1.92431 1.02483)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="c6y_tcclg"/><stop offset="1" class="bn4a00sgu"/></radialGradient><radialGradient id="i4VKWMc" cx="0" cy="0" r="1" gradientTransform="matrix(.40022 .6522 -1.5102 .92671 13.78 1.975)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="iadv6taec"/><stop offset="1" class="m3om6jjzt"/></radialGradient><radialGradient id="iRphd5b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68332 .60736 -.16904 -.4685 14.291 2.613)" gradientUnits="userSpaceOnUse"><stop class="ppo1r9bcz"/><stop offset="1" class="ijcelgbiw"/></radialGradient><radialGradient id="inDYtLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.42299 -2.25307 2.49617 1.57653 11.778 4.718)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="ltb-itmtt"/><stop offset=".233" class="pq3-kbbbz"/><stop offset="1" class="s-nb5j24l"/></radialGradient><radialGradient id="i4u9CsE" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -5.51 69.2)scale(1.53841 .86039)" gradientUnits="userSpaceOnUse"><stop class="cnfyfo5ds"/><stop offset="1" class="ysruzhx-p"/></radialGradient><radialGradient id="iYj0jgg" cx="0" cy="0" r="1" gradientTransform="matrix(-.95005 -1.63768 .91332 -.52984 16.447 5.162)" gradientUnits="userSpaceOnUse"><stop class="cneetrb1a"/><stop offset="1" class="p82f5nbfd"/></radialGradient><radialGradient id="iOrNJkc" cx="0" cy="0" r="1" gradientTransform="matrix(-.57808 -.9738 .69749 -.41406 16.173 5.03)" gradientUnits="userSpaceOnUse"><stop offset=".394" class="zrke-tbre"/><stop offset="1" class="pgiiwpbet"/></radialGradient><radialGradient id="ijuERJb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12173 .50903 -.55028 -2.29368 16.299 3.074)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="o1l86cbis"/><stop offset="1" class="ygp8qdbik"/></radialGradient><radialGradient id="iYjzgcF" cx="0" cy="0" r="1" gradientTransform="rotate(107.002 6.736 7.32)scale(.17743 .81119)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="o0qinnbwl"/><stop offset="1" class="ec7yarbjj"/></radialGradient><radialGradient id="ibaPN6w" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35917 -.5713 0 15.144 5.75)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iSkYSgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10267 -.1323 .18215 -.14135 15.043 5.786)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iaWUpgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35918 -.57132 0 13.215 5.75)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i0qp5Nd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 9.422 -3.52)scale(.21876 .26295)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i5DzEEc" cx="0" cy="0" r="1" gradientTransform="matrix(.27792 .99192 -.94637 .26516 16.221 5.755)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="vr5749b_g"/><stop offset="1" class="r9kx25b9b"/></radialGradient><radialGradient id="iq9Jumb" cx="0" cy="0" r="1" gradientTransform="matrix(.34834 -.47804 .40069 .29198 16.38 5.996)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="a8tdckb6o"/><stop offset="1" class="mfa5gim3o"/></radialGradient><radialGradient id="iYgPwTd" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 3.534 7.778)scale(.93594 .92012)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="bqhcerb-b"/><stop offset="1" class="g54wl109l"/></radialGradient><filter id="iLmWXXc" width="23.977" height="13.398" x="6.016" y="16.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="i6WHzqb" width="20.681" height="10.082" x="6.11" y="20.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".75"/></filter><filter id="idTb8Ey" width="24.344" height="8.644" x="2.007" y="21.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="iq2kkke" width="2.686" height="2.686" x="24.571" y="13.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="iP28t2d" width="2.186" height="2.186" x="27.821" y="11.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="iMjOTyc" width="1.928" height="1.928" x="25.946" y="9.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="ivvza9t" width="2.857" height="2.898" x="20.532" y="12.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.556863 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="iztH5ob" width="5.571" height="6.952" x="7.773" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.305882 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="i7avOnH" width="14.97" height="18.152" x="8.427" y="7.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.521569 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="iBTi4Ke" width="17.737" height="14.8" x="13.579" y="15.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation="1"/></filter><filter id="ir7G3Vd" width="6.506" height="14.75" x="14.572" y="7.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".375"/></filter><filter id="iglMucn" width="5.506" height="5.421" x="17.991" y="7.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".3"/></filter><filter id="inoILHb" width="2.83" height="3.282" x="12.673" y="4.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".5"/></filter><filter id="iOBjfUs" width="1.03" height="1.482" x="13.664" y="5.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".05"/></filter><filter id="irkR4kb" width="1.923" height=".975" x="13.218" y="7.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".05"/></filter><filter id="ijGJctV" width="5.692" height="3.974" x="11.333" y="1.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.509804 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.486275 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_5147_19643" result="effect2_innerShadow_5147_19643"/></filter><filter id="iL5Dwne" width="1.09" height=".638" x="14.882" y="4.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="izSurbe" width="1.09" height=".631" x="12.558" y="4.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.243137 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_5147_19643"/></filter><filter id="i2eQjab" width="3.19" height="2.908" x="11.351" y="2.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".125"/></filter><filter id="izjHAFb" width="3.02" height="2.777" x="14.041" y="2.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".125"/></filter><filter id="i21q0yc" width=".46" height=".42" x="14.764" y="5.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".05"/></filter><filter id="iUINDSc" width=".617" height=".627" x="15.079" y="5.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".1"/></filter><filter id="iLluEou" width=".66" height=".683" x="13.115" y="5.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".1"/></filter><filter id="iefQKdR" width=".516" height=".423" x="12.837" y="5.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".05"/></filter><filter id="iIxFrQd" width=".867" height="1.332" x="11.373" y="5.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".125"/></filter><filter id="iSgL88b" width=".919" height="1.343" x="16.123" y="5.368" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_5147_19643" stdDeviation=".125"/></filter><linearGradient id="ijJnbEe" x1="7.172" x2="16.735" y1="29.352" y2="29.352" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iMX3qoe" x1="16.86" x2="16.766" y1="30.258" y2="28.633" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="ila6ipb" x1="10.344" x2="9.579" y1="25.961" y2="26.023" gradientUnits="userSpaceOnUse"><stop class="vt7w43b0h"/><stop offset="1" class="z7xjq9sfn"/></linearGradient><linearGradient id="iQuJ98d" x1="21.172" x2="19.469" y1="21.914" y2="23" gradientUnits="userSpaceOnUse"><stop class="s_et88bec"/><stop offset="1" class="j4yrk8b8m"/></linearGradient><linearGradient id="iJ67Gde" x1="22.095" x2="23.329" y1="24.82" y2="26.102" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="inumkee" x1="5.891" x2="25.735" y1="29.227" y2="22.32" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="i792cHc" x1="15.777" x2="15.777" y1="7.594" y2="25.555" gradientUnits="userSpaceOnUse"><stop class="nmvycabwt"/><stop offset=".978" class="xujwu-wlk"/></linearGradient><linearGradient id="iRsy8Zd" x1="22.329" x2="16.517" y1="11.912" y2="8.537" gradientUnits="userSpaceOnUse"><stop class="ku_swbhun"/><stop offset=".888" class="upowizugn"/></linearGradient><linearGradient id="iBybyQb" x1="17.826" x2="20.269" y1="8.148" y2="21.384" gradientUnits="userSpaceOnUse"><stop class="e95gaqibw"/><stop offset="1" class="mtqjbpbdp"/></linearGradient><linearGradient id="iNeOQ4F" x1="22.438" x2="18.766" y1="11.867" y2="7.977" gradientUnits="userSpaceOnUse"><stop class="yjjppjb0c"/><stop offset="1" class="fvilr_bly"/></linearGradient><linearGradient id="i3w5fge" x1="14.179" x2="14.557" y1="6.521" y2="6.521" gradientUnits="userSpaceOnUse"><stop class="kc3wm8i6w"/><stop offset="1" class="st3dxnbfu"/></linearGradient><linearGradient id="ia4oiEd" x1="13.705" x2="14.18" y1="6.452" y2="6.478" gradientUnits="userSpaceOnUse"><stop class="abomb1boi"/><stop offset="1" class="pvsu__x5y"/><stop offset="1" class="ig7uz4g5n"/></linearGradient><linearGradient id="i7ZK5yd" x1="14.179" x2="14.179" y1="6.697" y2="7.074" gradientUnits="userSpaceOnUse"><stop class="pvsu__x5y"/><stop offset=".845" class="ag8lyyc-n"/></linearGradient><linearGradient id="i29E4Qd" x1="14.179" x2="14.179" y1="5.703" y2="5.889" gradientUnits="userSpaceOnUse"><stop class="zav_leb7s"/><stop offset="1" class="l5m23db_l"/></linearGradient><linearGradient id="iAF1lPc" x1="16.551" x2="12.075" y1="3.65" y2="3.65" gradientUnits="userSpaceOnUse"><stop class="r37rgng3f"/><stop offset="1" class="gcsbsh2mh"/></linearGradient><linearGradient id="iOqQqrh" x1="15.489" x2="15.35" y1="5.773" y2="5.859" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAF0g9U" x1="13.544" x2="13.405" y1="5.773" y2="5.859" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5tvMkd" x1="17.025" x2="16.492" y1="5.785" y2="6.747" gradientUnits="userSpaceOnUse"><stop class="dxsnshbck"/><stop offset="1" class="eihs-teph"/></linearGradient><linearGradient id="iiQaXwe" x1="11.593" x2="12.238" y1="6.096" y2="6.04" gradientUnits="userSpaceOnUse"><stop class="a9f7swmqb"/><stop offset="1" class="jr2wmk3hc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-surfing" /></template>
<style>
.a4fvj8bnp {
  d: path("M12.03 6.707a.73.73 0 0 1-.4-.137v.412a.96.96 0 0 0 .593.893a1.8 1.8 0 0 1-.153-.522z");
}

.a8tdckb6o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
}

.a9f7swmqb {
  stop-color: var(--svg-color--e39726, #E39726);
}

.abomb1boi {
  stop-color: var(--svg-color--f49f22, #F49F22);
}

.ae99og76i {
  cx: 26.86px;
  cy: 10.715px;
  r: 0.914px;
}

.ag8lyyc-n {
  stop-color: var(--svg-color--e88830, #E88830);
}

.azfgivboh {
  fill: var(--svg-color--000, #000);
  d: path("M14.92 5.933a.225.225 0 1 1 .427.104h-.401a.2.2 0 0 1-.027-.104");
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b2f11iceb {
  d: path("M11.945 5.332a.712.712 0 0 0 .06 1.415a35 35 0 0 1-.06-1.415");
}

.b5nd2m-sq {
  d: path("M16.329 6.707a.73.73 0 0 0 .4-.137v.412a.96.96 0 0 1-.593.893q.113-.24.153-.522z");
}

.b8-5lhb5p {
  stop-color: var(--svg-color--e39647, #E39647);
  stop-opacity: 0;
}

.b9qaylb2c {
  stop-color: var(--svg-color--d57a26, #D57A26);
}

.bg90e8h8i {
  d: path("M16.326 3.217a1.048 1.048 0 0 1 .514 1.582a.7.7 0 0 0-.12.386v.526a.8.8 0 0 0-.295-.119l.035-.71a.64.64 0 0 0-.61-.633h-.62c-.421 0-.804-.25-.977-.638a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.668-1.477 1.494l.013.68a.8.8 0 0 0-.318.116v-.53a.7.7 0 0 0-.12-.387a1.06 1.06 0 0 1-.063-1.082c.129-.244.337-.415.574-.498c.254-.09.47-.26.612-.49a1.03 1.03 0 0 1 1.279-.404a.66.66 0 0 0 .527 0a1.03 1.03 0 0 1 1.283.417c.136.226.35.39.598.475");
}

.bija72usz {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
}

.bjbw-ir7e {
  stop-color: var(--svg-color--ffb534, #FFB534);
  stop-opacity: 0;
}

.bkz_cdc-o {
  stop-color: var(--svg-color--e27426, #E27426);
}

.bn4a00sgu {
  stop-color: var(--svg-color--ffe639, #FFE639);
  stop-opacity: 0;
}

.bohes4bvb {
  stop-color: var(--svg-color--e39647, #E39647);
}

.bqhcerb-b {
  stop-color: var(--svg-color--c77937, #C77937);
  stop-opacity: 0;
}

.brt5yycyj {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.116 5.621c.029.038-.03.084-.097.134s-.117.085-.145.048s.003-.11.07-.16s.144-.06.172-.022");
}

.by5wrxbms {
  stop-color: var(--svg-color--e26839, #E26839);
}

.c6y_tcclg {
  stop-color: var(--svg-color--ffe639, #FFE639);
}

.c9oouybqp {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.602 7.223H13.6a.14.14 0 0 0-.17.03a.136.136 0 0 0-.014.171a.91.91 0 0 0 .762.407c.32 0 .601-.163.763-.407l-.062-.042l.062.042a.136.136 0 0 0-.015-.173a.14.14 0 0 0-.169-.028a1.25 1.25 0 0 1-.579.137c-.212 0-.411-.05-.578-.137Z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cneetrb1a {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
}

.cnfyfo5ds {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d2m2xebio {
  d: path("M13.575 5.887c0-.128-.104-.213-.132-.239l-.128.124l.079.16z");
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dnlo8zm8l {
  cx: 13.095px;
  cy: 5.707px;
  rx: 0.172px;
  ry: 0.087px;
}

.doutuqf7h {
  stop-color: var(--svg-color--ffb834, #FFB834);
}

.drevzvb2z {
  fill: var(--svg-color--ff702b, #FF702B);
  d: path("M10.684 11.684c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.031c.3-.027 1.148-.109 2.5-.718c1.679-.757 2.458-1.804 2.64-2.246l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.dxsnshbck {
  stop-color: var(--svg-color--ffe343, #FFE343);
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e95gaqibw {
  stop-color: var(--svg-color--ff965a, #FF965A);
}

.ec7yarbjj {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
  stop-opacity: 0;
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.eihs-teph {
  stop-color: var(--svg-color--ffc136, #FFC136);
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.f30_2gbsx {
  d: path("M14.18 7.435c-.225 0-.436-.053-.613-.145c-.06-.031-.126.037-.088.092a.84.84 0 0 0 .7.374c.294 0 .552-.15.7-.374c.039-.057-.026-.123-.087-.092a1.3 1.3 0 0 1-.613.145");
}

.f9qkq2bgn {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  fill-rule: evenodd;
  d: path("M5.611 14.932a.375.375 0 1 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 0 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fltjd-k8p {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
  stop-opacity: 0;
}

.frgrxi9fy {
  d: path("M10.684 11.684c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.031c.3-.027 1.148-.109 2.5-.718c1.679-.757 2.458-1.804 2.64-2.246l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.ft5dv1b6b {
  fill: none;
}

.fu31k5bmq {
  stop-color: var(--svg-color--ff5714, #FF5714);
}

.fvilr_bly {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
  stop-opacity: 0;
}

.g3hjbil2k {
  stop-color: var(--svg-color--89014e, #89014E);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gcsbsh2mh {
  stop-color: var(--svg-color--d29935, #D29935);
}

.ge106kfvz {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M15.83 4.837a.8.8 0 0 0-.304-.182c-.134-.043-.303-.054-.536-.026a.123.123 0 0 0 .03.244c.213-.026.343-.013.432.016a.6.6 0 0 1 .217.133a.123.123 0 1 0 .161-.185");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.gwjr899hs {
  d: path("M12.759 11.64c-.432-1.715.169-3.16.507-3.484l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.258c1.354 1.047 1.622 2.799 1.589 3.592a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.274-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.512 1.212 3.52c.546 1.484-.11 2.952.375 4.484c.377 1.191 1.203 2.418 1.636 2.92a.04.04 0 0 1-.013.063l-1.834.851a.04.04 0 0 1-.048-.01c-1.848-2.157-2.5-3.825-2.562-3.988c-.062-.165-.23-.532-.574-.532c-.275 0-.59.352-.809.73l-4.667 7.138a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.058c.21-.5.181-.916.14-1.085c-.03-.13-.218-.711-.585-2.172");
}

.gz8haxb3i {
  stop-color: var(--svg-color--d06a3c, #D06A3C);
}

.gzlr_0cpw {
  d: path("M16.356 6.747q.044-.705.081-1.411a.712.712 0 0 1-.081 1.411");
}

.h8-lgt47k {
  stop-color: var(--svg-color--de8137, #DE8137);
}

.hlw3e_blf {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.i34rybopj {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.797px;
  rx: 0.299px;
}

.i9-uutisp {
  d: path("M21.985 27.32L7.61 28.82c4.687-2.24 11.938-4.406 14.375-6.187c1.826-1.334 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.iadv6taec {
  stop-color: var(--svg-color--f3c130, #F3C130);
}

.iav904f4q {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
  stop-opacity: 0;
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ig7uz4g5n {
  stop-color: var(--svg-color--f49f22, #F49F22);
  stop-opacity: 0;
}

.ijcelgbiw {
  stop-color: var(--svg-color--ffdc2b, #FFDC2B);
  stop-opacity: 0;
}

.ilhw8v5oy {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  fill-rule: evenodd;
  d: path("M5.25 14.655q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a.7.7 0 0 0-.095.105");
}

.inzu6lb7s {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
  stop-opacity: 0;
}

.irvsablei {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  fill-rule: evenodd;
  d: path("M7.127 13.531c-.941-.283-1.295.01-1.388.12a.375.375 0 1 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 1 1-.216.718");
}

.itnwk0wzv {
  fill: var(--svg-color--ffc837, #FFC837);
  d: path("m16.373 6.46l.05-.842a.423.423 0 0 1-.05.842");
}

.j4yrk8b8m {
  stop-color: var(--svg-color--e28e5b, #E28E5B);
}

.j5xpxuvyt {
  cx: 13.095px;
  cy: 5.707px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.172px;
  ry: 0.087px;
}

.jhlh1_3ek {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.736H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jobbcdb5u {
  stop-color: var(--svg-color--ffc73f, #FFC73F);
}

.jr2wmk3hc {
  stop-color: var(--svg-color--d9851d, #D9851D);
}

.k-l9f-bpq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.122 5.418c-.289 0-.533.2-.599.468a.12.12 0 0 0 .118.15h.987a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.606-.498");
}

.kbjuoc3rc {
  stop-color: var(--svg-color--f59632, #F59632);
  stop-opacity: 0;
}

.kc3wm8i6w {
  stop-color: var(--svg-color--ffc92f, #FFC92F);
}

.ke8n9wjsm {
  stop-color: var(--svg-color--e18c2a, #E18C2A);
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kjlqo_13i {
  d: path("M15.497 5.881a.37.37 0 0 0-.102-.205l-.116.127l.052.1z");
}

.kr_erp7zc {
  d: path("m16.484 5.162l-.013-.279a.65.65 0 0 0-.621-.63h-.62a1.07 1.07 0 0 1-.939-.557s.319-.92.847-.8c.386.086.8.223 1.116.43c.771.502.636 1.41.23 1.836");
}

.ku_swbhun {
  stop-color: var(--svg-color--ff8444, #FF8444);
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l0ervjwrq {
  stop-color: var(--svg-color--ef972b, #EF972B);
}

.l0w5k5oua {
  d: path("M15.116 5.621c.029.038-.03.084-.097.134s-.117.085-.145.048s.003-.11.07-.16s.144-.06.172-.022");
}

.l5m23db_l {
  stop-color: var(--svg-color--fac137, #FAC137);
  stop-opacity: 0;
}

.l89w7ttua {
  fill-rule: evenodd;
  d: path("M7.127 13.531c-.941-.283-1.295.01-1.388.12a.375.375 0 1 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 1 1-.216.718");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljni-v35c {
  fill-rule: evenodd;
  d: path("M5.25 14.655q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a.7.7 0 0 0-.095.105");
}

.lppsh4wvc {
  stop-color: var(--svg-color--ffd930, #FFD930);
  stop-opacity: 0;
}

.ltb-itmtt {
  stop-color: var(--svg-color--d67227, #D67227);
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.m3om6jjzt {
  stop-color: var(--svg-color--f3c130, #F3C130);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfa5gim3o {
  stop-color: var(--svg-color--ffbd22, #FFBD22);
  stop-opacity: 0;
}

.mtqjbpbdp {
  stop-color: var(--svg-color--ff8064, #FF8064);
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n0_4eow9o {
  stop-color: var(--svg-color--ff875c, #FF875C);
  stop-opacity: 0;
}

.n8euy9vjg {
  stop-color: var(--svg-color--be691e, #BE691E);
}

.nf0740e8o {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
}

.nhjaj61fi {
  d: path("M15.145 5.538a.395.395 0 0 1 .381.5h-.763a.397.397 0 0 1 .383-.5");
}

.ninpi-65y {
  stop-color: var(--svg-color--ffb534, #FFB534);
}

.nmvycabwt {
  stop-color: var(--svg-color--ff7a3c, #FF7A3C);
}

.npu64rzpx {
  fill: var(--svg-color--c05029, #C05029);
  d: path("M12.671 4.788a1.23 1.23 0 0 1 .769-.159a.123.123 0 0 1-.03.244a.98.98 0 0 0-.646.147l-.007.005l-.002.001a.123.123 0 0 1-.15-.194z");
}

.o0qinnbwl {
  stop-color: var(--svg-color--ffce3c, #FFCE3C);
}

.o1l86cbis {
  stop-color: var(--svg-color--f29415, #F29415);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.olg-72bto {
  d: path("M16.782 13.438c-.65-1.28-1.166-3.185-1.443-4.424a.714.714 0 0 1 .588-.856c.447-.074.855.272.91.723c.205 1.698.95 3.373 1.445 4.682c.578 1.53.312 1.062.234 3.515c-.057 1.782 1.266 3.25 1.813 4.11l-.407.21c-.609-.828-2.203-2.945-2.203-4.851c0-1.791.063-1.14-.937-3.11");
}

.on9u00bey {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.273c1.209-.02 3.782.829 4.104 4");
}

.or_7yib9u {
  d: path("m14.01 5.838l-.235.813c-.048.167.067.334.23.334h.348c.163 0 .278-.17.23-.334l-.235-.813c-.05-.18-.285-.18-.338 0");
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.p82f5nbfd {
  stop-color: var(--svg-color--eb8f29, #EB8F29);
  stop-opacity: 0;
}

.pekg0u7cp {
  d: path("M20.68 13.837c.256-.588.373-1.22.399-1.462l2.047.024c.046.268-.04.583-.079.703c.088.322.037.687 0 .829c-.054.225-.178.713-.238.86c-.074.183-.183.246-.348.23a.4.4 0 0 1-.148-.043a.3.3 0 0 0-.23-.019a.43.43 0 0 1-.227.02a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.004a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.07c-.085.007-.183.002-.235-.042c-.098-.082-.219-.175.031-.746");
}

.pgiiwpbet {
  stop-color: var(--svg-color--e48421, #E48421);
  stop-opacity: 0;
}

.pjme70zim {
  fill: var(--svg-color--dd8224, #DD8224);
  d: path("M11.953 5.625a.423.423 0 0 0 .037.831a35 35 0 0 1-.037-.831");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmjfhr11v {
  d: path("M13.214 5.538a.395.395 0 0 0-.38.5h.763a.398.398 0 0 0-.383-.5");
}

.ppo1r9bcz {
  stop-color: var(--svg-color--ffdd30, #FFDD30);
}

.pq3-kbbbz {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
}

.pvsu__x5y {
  stop-color: var(--svg-color--e88830, #E88830);
  stop-opacity: 0;
}

.q-9x-2bzr {
  stop-color: var(--svg-color--ffd441, #FFD441);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qfyn005sz {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qnmjgylyq {
  d: path("M24.458 21.25L2.29 28.939a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.1 1.156-.156c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.378.605-.627v-.002c.094-.25.047-1.03-.5-1.453c-.437-.337-1.105-.185-1.355-.07");
}

.qny9ytbij {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  d: path("M6.126 14.875c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.qv62lactv {
  cx: 28.864px;
  cy: 12.801px;
  r: 1.043px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r2t9jab3e {
  stop-color: var(--svg-color--f5a129, #F5A129);
}

.r37rgng3f {
  stop-color: var(--svg-color--ffe235, #FFE235);
}

.r9kx25b9b {
  stop-color: var(--svg-color--e08f2e, #E08F2E);
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rw5mc4bto {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.237 5.418c.288 0 .533.2.599.468c.02.077-.04.15-.119.15h-.986a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .606-.498");
}

.s_et88bec {
  stop-color: var(--svg-color--ffd545, #FFD545);
}

.s-nb5j24l {
  stop-color: var(--svg-color--ef8a23, #EF8A23);
  stop-opacity: 0;
}

.s2ikxxbfc {
  cx: 25.864px;
  cy: 14.75px;
  r: 1.293px;
}

.s41d30h-g {
  stop-color: var(--svg-color--fe5346, #FE5346);
}

.s6k9w6bfo {
  fill: var(--svg-color--000, #000);
  d: path("M13.44 5.933c0-.126-.1-.226-.226-.226a.225.225 0 0 0-.201.33h.4a.2.2 0 0 0 .027-.104");
}

.sazwi3bdn {
  d: path("m23.469 25.315l-.422-1.143l-2.351.536l2.225 1.099a.396.396 0 0 0 .547-.492");
}

.siw2d1f7p {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("M21.985 27.32L7.61 28.82c4.687-2.24 11.938-4.406 14.375-6.187c1.826-1.334 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.so3eyo06u {
  d: path("M26.485 24.32c.981-2.278.626-3.887.055-5.013c-.474-.936-.003-1.662 1.018-1.421c.737.174 1.364.694 1.54 1.43c.721 3.026-.313 6.182-3.582 7.817c-2.95 1.475-7.854 1.594-9.937 1.469c3 0 9.804-1.723 10.906-4.282");
}

.st3dxnbfu {
  stop-color: var(--svg-color--ffea47, #FFEA47);
}

.swgfs-c3o {
  stop-color: var(--svg-color--ffd930, #FFD930);
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.tc7qg6b0q {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  fill-rule: evenodd;
  d: path("M5.404 14.127s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.u--ocwryb {
  d: path("M19.837 23a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.u7o3559vd {
  stop-color: var(--svg-color--f59632, #F59632);
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.upowizugn {
  stop-color: var(--svg-color--ff783f, #FF783F);
}

.uu4f6-byw {
  d: path("M6.126 14.875c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vb809lo-e {
  d: path("M19.75 29.736H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.ven54yrxx {
  stop-color: var(--svg-color--c98537, #C98537);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vr5749b_g {
  stop-color: var(--svg-color--e1943d, #E1943D);
  stop-opacity: 0;
}

.vt7w43b0h {
  stop-color: var(--svg-color--ffaf2e, #FFAF2E);
}

.wbf-2ib5u {
  stop-color: var(--svg-color--ffe846, #FFE846);
}

.wc05b2bod {
  fill-rule: evenodd;
  d: path("M5.611 14.932a.375.375 0 1 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 0 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.wnm4h6zib {
  d: path("M12.046 7.377a1.73 1.73 0 0 0 1.718 1.506h.834a1.73 1.73 0 0 0 1.718-1.506c.053-.833.105-1.663.144-2.495a.64.64 0 0 0-.61-.633h-.62c-.421 0-.803-.25-.977-.638a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.668-1.477 1.494c0 .822.05 1.632.105 2.457");
}

.woc0miqaj {
  stop-color: var(--svg-color--fe5346, #FE5346);
  stop-opacity: 0;
}

.wrlksbcrj {
  stop-color: var(--svg-color--c98537, #C98537);
  stop-opacity: 0;
}

.wwr7m_5oe {
  stop-color: var(--svg-color--ffbe3a, #FFBE3A);
  stop-opacity: 0;
}

.wxscdbbqi {
  stop-color: var(--svg-color--ffb52a, #FFB52A);
  stop-opacity: 0;
}

.x2d1t4xtf {
  fill-rule: evenodd;
  d: path("M5.404 14.127s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.xitcw8bap {
  stop-color: var(--svg-color--ffc135, #FFC135);
}

.xt887yc-y {
  d: path("M17.568 10.265a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.545-1.589-3.592c-1.381-1.07-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.671");
}

.xtp47zbsj {
  d: path("m7.305 27.336l1.172-2.39l1.766.304v1.04z");
}

.xujwu-wlk {
  stop-color: var(--svg-color--ff4d30, #FF4D30);
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y3p74o-xo {
  fill: var(--svg-color--ee9020, #EE9020);
  d: path("m13.965 5.925l-.281.813c-.048.167.067.334.23.334h.348c.163 0 .278-.17.23-.334l-.235-.813c-.05-.18-.24-.18-.293 0");
}

.y6c1p2x8v {
  d: path("m14.282 3.671l-.03-.06a.29.29 0 0 0-.271-.185h-.563c-.816 0-1.478.668-1.478 1.494v.121c-.15-.114-.339-.355-.339-.746c0-.474.346-.713.566-.866c.062-.043.115-.08.146-.112l.044-.047c.155-.163.43-.456.911-.583q.108-.03.216-.045c.467-.073.807.346.807.819v.204z");
}

.ygp8qdbik {
  stop-color: var(--svg-color--f29415, #F29415);
}

.yhtyhvpuw {
  stop-color: var(--svg-color--ffa041, #FFA041);
  stop-opacity: 0;
}

.yjjppjb0c {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
}

.ysruzhx-p {
  stop-color: var(--svg-color--ffeb3b, #FFEB3B);
  stop-opacity: 0;
}

.yt5sdf2gy {
  stop-color: var(--svg-color--ff875c, #FF875C);
}

.z7xjq9sfn {
  stop-color: var(--svg-color--ffaf2e, #FFAF2E);
  stop-opacity: 0;
}

.z8auuww1t {
  stop-color: var(--svg-color--be691e, #BE691E);
  stop-opacity: 0;
}

.zav_leb7s {
  stop-color: var(--svg-color--fac137, #FAC137);
}

.zkqd2ycat {
  stop-color: var(--svg-color--ff5714, #FF5714);
  stop-opacity: 0;
}

.zrke-tbre {
  stop-color: var(--svg-color--e48421, #E48421);
}

.ztrk-1hpr {
  stop-color: var(--svg-color--ffbe42, #FFBE42);
}

.zyhd--c_o {
  fill: var(--svg-color--ffbd2e, #FFBD2E);
  d: path("M7.563 12.766h.594c-.106.668.07 1.611.172 2c-1.007.13-1.696-.112-1.914-.25l-.11-1.461c.332-.257.977-.3 1.258-.29");
}

</style>
