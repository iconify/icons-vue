<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i1mfzFc)" class="exu879bgq"/><path fill="url(#ikSmZec)" class="exu879bgq"/><path fill="url(#ijW2tCc)" class="exu879bgq"/><path fill="url(#iBUdF1U)" class="exu879bgq"/><path fill="url(#i5fkc5d)" class="exu879bgq"/><path fill="url(#ikOdTnr)" class="exu879bgq"/><path fill="url(#iZORvqc)" class="exu879bgq"/><path fill="url(#ikaC8Fd)" class="exu879bgq"/><path fill="url(#idet8zc)" class="exu879bgq"/><path fill="url(#i7BdGlh)" class="exu879bgq"/><path fill="url(#i8sQkVI)" class="exu879bgq"/><g filter="url(#iHl0Dab)"><path stroke="url(#iay7y6d)" class="khd7pkb9d"/></g><g filter="url(#iXswJrd)"><path stroke="url(#ibIKF5d)" class="h61awobxy"/></g><g filter="url(#iOE1LMc)"><path stroke="url(#iD5cZUb)" class="m58fx9l3v"/></g><g filter="url(#iq7Xv5d)"><path stroke="url(#iLtS7Jd)" class="gffm9pbit"/></g><g filter="url(#iCTOtAb)"><path stroke="url(#iIzzekd)" class="mi0d6giae"/></g><g filter="url(#iIaCree)"><path stroke="url(#iCjjMlc)" class="x5paccbok"/></g><g filter="url(#iL4WMVd)"><path stroke="url(#irTASvd)" class="pt7s1qkku"/></g><g filter="url(#iAwfuhe)"><path stroke="url(#iAwe7wb)" class="og5w2nb6h"/></g><g filter="url(#ie6paqP)"><path stroke="url(#iSNbosb)" class="uj0weyjko"/></g><g filter="url(#iaQckUc)"><path stroke="url(#iXB1BYH)" class="glfetwbqa"/></g><g filter="url(#iDZKiUu)"><path fill="url(#iGuGjve)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#izBnVxi)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#iGUareC)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#i5Hrsbe)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#iLJMjFc)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#i9kU9zS)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#ioH2LJc)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#ivryakd)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#iQEBnyd)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#iCJBJEB)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#inxJWyb)" clip-rule="evenodd" class="uw6orsblr"/><path fill="url(#iM2DpxC)" clip-rule="evenodd" class="uw6orsblr"/></g><path fill="url(#iNJBdkU)" class="b5g3i3mag"/><path fill="url(#iidsVGS)" class="b5g3i3mag"/><path fill="url(#idB9Qhe)" class="b5g3i3mag"/><path fill="url(#i72TxPd)" class="zar_-tbdp"/><path fill="url(#i2Q42Cd)" class="zar_-tbdp"/><path fill="url(#ierll2n)" class="zar_-tbdp"/><path fill="url(#id8vtIc)" class="zoqmhxs6u"/><path fill="url(#iu5VJGd)" class="zoqmhxs6u"/><path fill="url(#ifUceYy)" class="zoqmhxs6u"/><path fill="url(#icgRCed)" class="zoqmhxs6u"/><path fill="url(#iaaTy8d)" class="zoqmhxs6u"/><path fill="url(#ilN7RCM)" class="zoqmhxs6u"/><path fill="url(#ilryHbe)" class="xrgpjcb6i"/><g filter="url(#i4hUzPc)"><path stroke="url(#iAXZo0S)" class="phx3m2o6y"/></g><g filter="url(#iVDJAoe)"><path fill="url(#iiHvxLd)" class="e4n4qif-p"/></g><path fill="url(#i3hMlJU)" class="e4n4qif-p"/><g filter="url(#iiur3ae)"><path fill="url(#i3OwcUc)" class="vt-rtgbrf"/><path fill="url(#iQtBfjc)" class="vt-rtgbrf"/></g><g filter="url(#iZs9Pmb)"><path class="cu-_gbbeh"/><path fill="url(#iC5xwWd)" class="cx93g4bax"/></g><g filter="url(#iZX5kBd)"><path class="tn-b1ujph"/><path fill="url(#i94Dyyb)" class="fa1d93bwu"/></g><g filter="url(#iuuQUdd)"><path fill="url(#iVocTee)" class="emwbs-wyd"/><path fill="url(#iHc2PZc)" class="emwbs-wyd"/><path fill="url(#i2P9Cre)" class="emwbs-wyd"/><path fill="url(#iF55CWd)" class="emwbs-wyd"/><path fill="url(#iA00Bge)" class="emwbs-wyd"/><path fill="url(#ixcORYb)" class="emwbs-wyd"/><path fill="url(#iG22XYb)" class="emwbs-wyd"/><path fill="url(#iLe4Gcc)" class="emwbs-wyd"/><path fill="url(#i4W4I8Y)" class="emwbs-wyd"/></g><path fill="url(#iNCiOre)" class="emwbs-wyd"/><g filter="url(#i9uvhfd)"><path class="k62cnfbxt"/></g><g filter="url(#iz7UaOe)"><path class="fw0pejbna"/><path fill="url(#icw5BEe)" class="t-8ibsbxr"/><path fill="url(#iSN0vXP)" class="t-8ibsbxr"/><path fill="url(#iohEmyx)" class="t-8ibsbxr"/><path fill="url(#iW7UdHQ)" class="t-8ibsbxr"/></g><path fill="url(#i9iyz4d)" class="t-8ibsbxr"/><path fill="url(#iqYI0Sc)" class="t-8ibsbxr"/><path stroke="url(#i6hHoLd)" class="d3hq8ub7z"/><g filter="url(#iTBBoPe)"><path class="zn-badfuu"/></g><g filter="url(#iewCq0b)"><path class="g-h4rzbcg"/></g><g filter="url(#iZABsFe)"><path class="lyo57mnwh"/></g><g filter="url(#ipH2Ebc)"><path clip-rule="evenodd" class="vduttcjap"/></g><path class="nvs1l4bzh"/><path fill="url(#iFJBMRb)" class="n66cvvb5y"/><path class="p80yl1i4o"/><g filter="url(#i1ruwkc)"><path class="x97mw867e"/><path fill="url(#idXXCJb)" class="qzl83lbyv"/></g><g filter="url(#iQ81S8d)"><path fill="url(#iItTzLe)" class="txryfdvnp"/></g><path class="r-j4-wrap"/><path fill="url(#iGvtPoj)" class="x21r1dbcr"/><path class="dz04i7o9z"/><g filter="url(#ipag6qc)"><path fill="url(#iAYsele)" class="elp7nabxh"/></g><g filter="url(#ic5TZfc)"><ellipse transform="rotate(-27.914 15.706 13.22)" class="oct_5_7qz"/><ellipse fill="url(#ibLX0yb)" transform="rotate(-27.914 15.706 13.22)" class="j0x8wibsd"/></g><g filter="url(#iTPjwbb)"><path class="eiy7ksrtd"/></g><g filter="url(#i4qZ2hb)"><path class="w6tqyubjs"/></g><g filter="url(#ihObJRK)"><path class="k-bk0xbne"/><path fill="url(#iag4kqd)" class="rrtp5_b4o"/><path fill="url(#iI0msgb)" class="rrtp5_b4o"/></g><g filter="url(#ikzIhtb)"><path class="do-y-9_2j"/><path fill="url(#inF2szd)" class="yjwsesbit"/><path fill="url(#iMrK1fe)" class="yjwsesbit"/></g><g filter="url(#iRmqVJb)"><path stroke="url(#itQBvBe)" class="rawj5ubfs"/></g><g filter="url(#irVcaae)"><path class="sg-pxqbvz"/></g><defs><radialGradient id="i1mfzFc" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 5.783 11.432)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="pr1c_plua"/><stop offset="1" class="qdtuxcc3i"/></radialGradient><radialGradient id="ikSmZec" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 2.837 7.074)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="h0kcnqbkf"/><stop offset="1" class="kybxapb2q"/></radialGradient><radialGradient id="iBUdF1U" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.508 4.618)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="t6ahfk42q"/><stop offset="1" class="lnx1w7b3f"/></radialGradient><radialGradient id="i5fkc5d" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 6.156 3.454)" gradientUnits="userSpaceOnUse"><stop offset=".401" class="t6ahfk42q"/><stop offset="1" class="lnx1w7b3f"/></radialGradient><radialGradient id="ikOdTnr" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 3.96875 -.56716 -.09602 8.125 2.688)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="t6ahfk42q"/><stop offset="1" class="lnx1w7b3f"/></radialGradient><radialGradient id="iZORvqc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 9.623 3.049)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="ikaC8Fd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 7.698 2.021)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="idet8zc" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.718 3.676)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="i7BdGlh" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 3.883 3.836)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="i8sQkVI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09125 1.09125 -.85394 -.85394 11.92 6.319)" gradientUnits="userSpaceOnUse"><stop class="ww76qh22b"/><stop offset="1" class="lejfwxzry"/></radialGradient><radialGradient id="izBnVxi" cx="0" cy="0" r="1" gradientTransform="rotate(97.539 1.664 16.61)scale(5.64508 7.05185)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iGUareC" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53891 2.38667 -3.1359 -4.64985 14.891 17.468)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="i5Hrsbe" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.842 10.326)scale(2.64189 2.0286)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iLJMjFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.58426 2.59239 -1.8261 -1.11597 13.327 11.852)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="i9kU9zS" cx="0" cy="0" r="1" gradientTransform="matrix(1.68712 3.20963 -4.45545 2.34197 14.397 4.177)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="ioH2LJc" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 11.545 8.724)scale(2.50226 3.49686)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="ivryakd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2631 .6584 -1.37302 -4.71952 27.935 13.024)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="iQEBnyd" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 12.537 10.285)scale(3.56281 4.53849)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iCJBJEB" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 15.854 -3.755)scale(3.43743 2.71881)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="inxJWyb" cx="0" cy="0" r="1" gradientTransform="matrix(1.84606 .19364 -.31376 2.99116 11.179 12.98)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iM2DpxC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02871 -4.54698 1.6411 -.37128 24.993 12.18)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iidsVGS" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -1.15625 0 6.835 12.039)" gradientUnits="userSpaceOnUse"><stop class="vm40c2rnb"/><stop offset="1" class="in_wled_m"/></radialGradient><radialGradient id="i2Q42Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.05789 2.36576 -2.0517 -6.98818 25.18 27.22)" gradientUnits="userSpaceOnUse"><stop class="cedqx2rkm"/><stop offset="1" class="xi0shyhbu"/></radialGradient><radialGradient id="ierll2n" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.65624 0 10.595 29.586)" gradientUnits="userSpaceOnUse"><stop class="fp2gw167u"/><stop offset="1" class="rnij5z0qd"/></radialGradient><radialGradient id="iu5VJGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.65452 -5.4375 0 2.648 12.586)" gradientUnits="userSpaceOnUse"><stop class="rz1t4jbgv"/><stop offset="1" class="xkxmx1bvv"/></radialGradient><radialGradient id="ifUceYy" cx="0" cy="0" r="1" gradientTransform="rotate(-168.087 9.721 9.023)scale(10.3318 4.37074)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="m2mta8b_j"/><stop offset="1" class="tx_pqhb7h"/></radialGradient><radialGradient id="icgRCed" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69115 0 0 -5.6259 11.418 15.446)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m2mta8b_j"/><stop offset="1" class="tx_pqhb7h"/></radialGradient><radialGradient id="ilryHbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.96875 3.9375 -4.4375 2.21876 17.875 19.343)" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ao9_-bbfj"/><stop offset="1" class="op15yplgp"/></radialGradient><radialGradient id="i3hMlJU" cx="0" cy="0" r="1" gradientTransform="matrix(-.80241 -1.47725 1.67393 -.90925 12.484 16.045)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="i3OwcUc" cx="0" cy="0" r="1" gradientTransform="matrix(3.05533 -1.38879 1.69564 3.7304 23.677 14.609)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iQtBfjc" cx="0" cy="0" r="1" gradientTransform="matrix(1.48137 0 0 .63781 24.787 11.975)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iC5xwWd" cx="0" cy="0" r="1" gradientTransform="matrix(1.8534 -.13787 .10777 1.44884 24.108 14.207)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i94Dyyb" cx="0" cy="0" r="1" gradientTransform="rotate(-180 6.535 7.035)scale(1.2962)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iVocTee" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 9.642 9.144)scale(8.79107 11.7667)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iHc2PZc" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 9.048 9.451)scale(2.92395 2.03619)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="i2P9Cre" cx="0" cy="0" r="1" gradientTransform="matrix(1.58243 -4.82208 6.11832 2.00782 16.064 21.398)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iF55CWd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57695 9.05062 -11.31316 -1.97117 19.974 12.899)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ndb61xwjr"/><stop offset="1" class="l57p2o49o"/></radialGradient><radialGradient id="iA00Bge" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.69487 -7.73608 0 18.397 13.889)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="i-c7amj6z"/><stop offset="1" class="nmcs74byh"/></radialGradient><radialGradient id="ixcORYb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.47672 1.66353 -2.86409 -14.59432 20.94 15.534)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="iG22XYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41257 1.73361 0 21.543 12.896)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iLe4Gcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.61111 1.84645 0 16.17 12.616)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="i4W4I8Y" cx="0" cy="0" r="1" gradientTransform="matrix(-1.06812 3.96084 -3.16932 -.85467 20.416 10.053)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iNCiOre" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57769 0 0 -7.91196 24.973 14.722)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="icw5BEe" cx="0" cy="0" r="1" gradientTransform="rotate(-102.564 16.1 -.082)scale(2.57059 .79223)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iW7UdHQ" cx="0" cy="0" r="1" gradientTransform="matrix(-.95672 0 0 -.26747 19.387 15.874)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iqYI0Sc" cx="0" cy="0" r="1" gradientTransform="rotate(145.529 7.241 10.547)scale(2.04165 2.45375)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="iFJBMRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9959 -1.58408 0 21.396 13.337)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="idXXCJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28468 -.36685 .50506 -.39193 21.116 13.44)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGvtPoj" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9959 -1.58409 0 16.04 13.337)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ibLX0yb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0095 -.60646 .72899 -.01141 15.688 13.606)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iag4kqd" cx="0" cy="0" r="1" gradientTransform="matrix(1.54914 -3.3823 1.7303 .7925 11.773 10.734)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="iI0msgb" cx="0" cy="0" r="1" gradientTransform="matrix(1.41105 -2.42462 1.30168 .75754 13.869 9.53)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="inF2szd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.59243 5.39052 -8.81319 -4.23847 21.064 4.342)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="iMrK1fe" cx="0" cy="0" r="1" gradientTransform="matrix(-.25819 1.67824 -3.61064 -.55548 18.976 4.795)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="iHl0Dab" width=".423" height="2.22" x="4.363" y="4.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".05"/></filter><filter id="iXswJrd" width=".345" height="2.572" x="5.917" y="4.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".05"/></filter><filter id="iOE1LMc" width=".509" height="1.681" x="7.394" y="4.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".05"/></filter><filter id="iq7Xv5d" width="1.556" height="3.487" x="3.228" y="3.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".2"/></filter><filter id="iCTOtAb" width="1.2" height="3.889" x="4.914" y="3.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".2"/></filter><filter id="iIaCree" width="1.488" height="4.773" x="6.461" y="2.14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".2"/></filter><filter id="iL4WMVd" width="2.002" height="4.299" x="7.865" y="3.155" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".2"/></filter><filter id="iAwfuhe" width="1.412" height="1.358" x="3.519" y="6.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".1"/></filter><filter id="ie6paqP" width="1.118" height=".999" x="5.167" y="6.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".1"/></filter><filter id="iaQckUc" width="1.312" height="1.023" x="6.432" y="6.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".1"/></filter><filter id="iDZKiUu" width="18.685" height="19.185" x="9.5" y="2.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/></filter><filter id="i4hUzPc" width="9.217" height="11.911" x="5.06" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".75"/></filter><filter id="iVDJAoe" width="4.1" height="3.95" x="10.991" y="12.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/></filter><filter id="iiur3ae" width="3.95" height="4.2" x="22.668" y="11.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/></filter><filter id="iZs9Pmb" width="3.637" height="3.637" x="22.825" y="12.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".25"/></filter><filter id="iZX5kBd" width="3.337" height="3.337" x="11.322" y="12.401" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".175"/></filter><filter id="iuuQUdd" width="12.509" height="13.751" x="12.463" y="8.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/></filter><filter id="i9uvhfd" width="3.304" height="4.292" x="16.866" y="12.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".25"/></filter><filter id="iz7UaOe" width="2.804" height="3.792" x="17.316" y="13.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".125"/></filter><filter id="iTBBoPe" width="3.639" height="1.578" x="19.92" y="12.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/></filter><filter id="iewCq0b" width="3.639" height="1.578" x="13.878" y="12.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/></filter><filter id="iZABsFe" width="2.965" height="1.294" x="14.043" y="10.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/></filter><filter id="ipH2Ebc" width="2.965" height="1.294" x="20.693" y="10.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/></filter><filter id="i1ruwkc" width=".92" height=".809" x="20.518" y="12.82" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".05"/></filter><filter id="iQ81S8d" width="1.003" height="1.03" x="21.572" y="12.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".1"/></filter><filter id="ipag6qc" width="1.12" height="1.186" x="16.118" y="12.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".1"/></filter><filter id="ic5TZfc" width="1.075" height=".819" x="15.169" y="12.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".05"/></filter><filter id="iTPjwbb" width="2.839" height="1.264" x="20.699" y="10.716" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".1"/></filter><filter id="i4qZ2hb" width="2.639" height="1.064" x="14.107" y="10.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".1"/></filter><filter id="ihObJRK" width="5.088" height="5.458" x="11.009" y="5.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/><feGaussianBlur result="effect2_foregroundBlur_4002_3869" stdDeviation=".2"/></filter><filter id="ikzIhtb" width="10.637" height="6.984" x="14.895" y="4.213" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3869"/><feGaussianBlur result="effect2_foregroundBlur_4002_3869" stdDeviation=".125"/></filter><filter id="iRmqVJb" width="1.269" height="2.699" x="14.869" y="5.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".1"/></filter><filter id="irVcaae" width="8.048" height="4.298" x="17.595" y="6.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3869" stdDeviation=".5"/></filter><linearGradient id="ijW2tCc" x1="6.266" x2="6.266" y1="12.092" y2="10.389" gradientUnits="userSpaceOnUse"><stop class="sy2nhlbqj"/><stop offset="1" class="o6qx6mc1p"/></linearGradient><linearGradient id="iay7y6d" x1="4.756" x2="3.804" y1="4.785" y2="6.571" gradientUnits="userSpaceOnUse"><stop class="a53shnb1b"/><stop offset="1" class="hsqf8hwha"/></linearGradient><linearGradient id="ibIKF5d" x1="6.176" x2="4.875" y1="4.356" y2="5.336" gradientUnits="userSpaceOnUse"><stop class="a53shnb1b"/><stop offset="1" class="hsqf8hwha"/></linearGradient><linearGradient id="iD5cZUb" x1="7.935" x2="7.553" y1="4.956" y2="6.521" gradientUnits="userSpaceOnUse"><stop class="a53shnb1b"/><stop offset="1" class="hsqf8hwha"/></linearGradient><linearGradient id="iLtS7Jd" x1="3.522" x2="3.941" y1="4.898" y2="7.505" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="iIzzekd" x1="4.666" x2="4.878" y1="4.025" y2="7.148" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="iCjjMlc" x1="6.816" x2="7.918" y1="3.268" y2="6.945" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="irTASvd" x1="7.77" x2="8.086" y1="4.218" y2="7.649" gradientUnits="userSpaceOnUse"><stop class="px0vdqe0d"/><stop offset="1" class="ik287t08j"/></linearGradient><linearGradient id="iAwe7wb" x1="4.816" x2="3.724" y1="6.765" y2="6.697" gradientUnits="userSpaceOnUse"><stop class="xgo-prp7n"/><stop offset="1" class="krd2fabda"/></linearGradient><linearGradient id="iSNbosb" x1="6.088" x2="5.524" y1="6.593" y2="6.452" gradientUnits="userSpaceOnUse"><stop class="xgo-prp7n"/><stop offset="1" class="krd2fabda"/></linearGradient><linearGradient id="iXB1BYH" x1="7.589" x2="6.786" y1="6.406" y2="6.193" gradientUnits="userSpaceOnUse"><stop class="xgo-prp7n"/><stop offset="1" class="krd2fabda"/></linearGradient><linearGradient id="iGuGjve" x1="24.479" x2="16.948" y1="5.535" y2="18.744" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iNJBdkU" x1="3.904" x2="8.279" y1="12.149" y2="12.149" gradientUnits="userSpaceOnUse"><stop class="u-9w58unm"/><stop offset=".743" class="gv7qteejy"/></linearGradient><linearGradient id="idB9Qhe" x1="6.174" x2="6.174" y1="11.563" y2="11.82" gradientUnits="userSpaceOnUse"><stop class="s68njbc8b"/><stop offset="1" class="ha46_3b_b"/></linearGradient><linearGradient id="i72TxPd" x1="18.688" x2="5.165" y1="28.764" y2="12.586" gradientUnits="userSpaceOnUse"><stop class="dkttnh3ka"/><stop offset=".751" class="j0qmv8b6d"/></linearGradient><linearGradient id="id8vtIc" x1="9.133" x2="11.026" y1="26.009" y2="19.818" gradientUnits="userSpaceOnUse"><stop offset=".1" class="nrxnoi8to"/><stop offset="1" class="o8-s5pjlc"/></linearGradient><linearGradient id="iaaTy8d" x1="13.471" x2="12.687" y1="24.32" y2="22.687" gradientUnits="userSpaceOnUse"><stop class="hzm5vwgac"/><stop offset=".732" class="yy_71ub6o"/></linearGradient><linearGradient id="ilN7RCM" x1="6.662" x2="6.662" y1="12.586" y2="13.608" gradientUnits="userSpaceOnUse"><stop class="ignlpnblb"/><stop offset="1" class="a8kog2b_j"/></linearGradient><linearGradient id="iAXZo0S" x1="6.717" x2="12.467" y1="14.294" y2="22.575" gradientUnits="userSpaceOnUse"><stop class="ius0mclhc"/><stop offset="1" class="f3d24-ppq"/></linearGradient><linearGradient id="iiHvxLd" x1="10.991" x2="13.271" y1="14.177" y2="14.177" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iSN0vXP" x1="17.566" x2="18.718" y1="15.704" y2="15.704" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iohEmyx" x1="18.718" x2="18.718" y1="16.572" y2="15.802" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="i9iyz4d" x1="18.814" x2="18.814" y1="16.652" y2="16.481" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="i6hHoLd" x1="17.411" x2="17.977" y1="18.415" y2="17.541" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iItTzLe" x1="22.351" x2="21.966" y1="13.403" y2="13.64" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAYsele" x1="16.953" x2="16.567" y1="13.403" y2="13.64" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itQBvBe" x1="14.902" x2="15.503" y1="5.536" y2="7.089" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-raising-hand-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a53shnb1b {
  stop-color: var(--svg-color--724736, #724736);
}

.a8kog2b_j {
  stop-color: var(--svg-color--6a51a2, #6A51A2);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.ao9_-bbfj {
  stop-color: var(--svg-color--935d65, #935D65);
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.b5g3i3mag {
  d: path("M4.068 11.763c0-.11.09-.2.2-.2H8.08c.11 0 .2.09.2.2v1.714H4.07z");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.cedqx2rkm {
  stop-color: var(--svg-color--9e7fdf, #9E7FDF);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-_gbbeh {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M24.643 15.388a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.cx93g4bax {
  d: path("M24.643 15.388a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.d3hq8ub7z {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.996 17.176a3.66 3.66 0 0 0 1.722.418c.637 0 1.224-.152 1.721-.418a.24.24 0 0 1 .29.049a.23.23 0 0 1 .025.292m-3.758-.34l3.716.313m-3.716-.314a.24.24 0 0 0-.29.051a.23.23 0 0 0-.024.29m.314-.34l-.272.313m4.03.027l-.042-.027m.042.027l-.042-.027m.042.027a2.42 2.42 0 0 1-4.072 0m4.03-.027a2.372 2.372 0 0 1-3.988 0m-.042.027l.042-.027m-.042.027l.042-.027");
}

.dkttnh3ka {
  stop-color: var(--svg-color--8663c9, #8663C9);
}

.do-y-9_2j {
  fill: var(--svg-color--553836, #553836);
  d: path("M17.977 4.507c-1.39-.307-2.638 1.08-2.782 1.594c1.29 4.352 4.557 4.113 7.782 3.755c1.93-.215 2.14.665 2.304 1.09c0-4.827-4.105-5.733-7.268-6.432z");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dz04i7o9z {
  fill: var(--svg-color--000, #000);
  d: path("M16.664 13.847a.625.625 0 0 0-.627-.628a.625.625 0 0 0-.558.917h1.11a.6.6 0 0 0 .075-.29");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4n4qif-p {
  d: path("M12.966 16.045a1.975 1.975 0 1 0 0-3.95a1.975 1.975 0 0 0 0 3.95");
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eiy7ksrtd {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.099 11.157c.396-.096 1.38-.048 2.038.423");
}

.elp7nabxh {
  d: path("M17.038 13.718c0-.354-.288-.59-.366-.661l-.354.342l.218.443z");
}

.emwbs-wyd {
  d: path("M12.473 12.52h.016l-.013-.326l-.013-.376c.026-1.164.705-1.615.995-1.766q.029-.01.063-.025l.063-.025a2.83 2.83 0 0 0 1.46-1.515l.1-.238a.324.324 0 0 1 .567-.063a4.74 4.74 0 0 0 3.915 2.054h3.952c.221 0 1.329.107 1.395 1.636l-.146 3.772c-.151 3.44-2.838 5.75-6.117 5.75s-5.966-2.31-6.117-5.75z");
}

.exu879bgq {
  d: path("M3.204 8.795c-.125-1.922-.282-2.958-.329-3.64c-.035-.513.024-1.067.711-1.192c.598-.074.883.452.907.66c-.003-.2 0-.68 0-.804c0-.211.007-.977.859-.977c.601 0 .816.587.8.863c.011-.101.023-.413.036-.707c.018-.433.252-.989.945-.976c.598.039.793.613.766.976l-.117 1.867c.023-.187.102-.664.277-1.34c.175-.674.702-.72.957-.683c.326.046.88.36.649 1.273c-.275 1.157-.463 2.645-.528 3.286c.324-.133.643-.413 1.002-.788c.36-.375.887-.383 1.184-.16c.34.293.521.967.119 1.37c-.463.424-2.129 2.404-2.957 3.394c-.23.292-.997.875-2.235.875c-2.203-.094-2.941-1.676-3.046-3.297");
}

.f3d24-ppq {
  stop-color: var(--svg-color--9478ce, #9478CE);
  stop-opacity: 0;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa1d93bwu {
  d: path("M12.99 15.388a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.fp2gw167u {
  stop-color: var(--svg-color--8969ba, #8969BA);
}

.ft5dv1b6b {
  fill: none;
}

.fw0pejbna {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m18.249 13.626l-.653 2.087a.662.662 0 0 0 .64.859h.965a.664.664 0 0 0 .639-.859l-.653-2.087c-.14-.462-.792-.462-.938 0");
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g-h4rzbcg {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M17.316 13.371c-.325-.573-.82-1.026-1.887-1.026c-.467 0-.917.13-1.317.453c-.33.267-.286.608-.03.736l.683.39c.8-.26 1.685-.294 2.551-.553");
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gffm9pbit {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m3.826 4.422l.36 2.632");
}

.glfetwbqa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.445 6.413c-.13.165-.502.36-.712.423");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gv7qteejy {
  stop-color: var(--svg-color--463168, #463168);
}

.h0kcnqbkf {
  stop-color: var(--svg-color--814f57, #814F57);
}

.h61awobxy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m6.125 4.352l-.07 2.297");
}

.ha46_3b_b {
  stop-color: var(--svg-color--4f396f, #4F396F);
  stop-opacity: 0;
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hsqf8hwha {
  stop-color: var(--svg-color--724736, #724736);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.hzm5vwgac {
  stop-color: var(--svg-color--8967cb, #8967CB);
}

.i-c7amj6z {
  stop-color: var(--svg-color--9f6394, #9F6394);
  stop-opacity: 0;
}

.ignlpnblb {
  stop-color: var(--svg-color--6a51a2, #6A51A2);
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.ik287t08j {
  stop-color: var(--svg-color--c09a87, #C09A87);
  stop-opacity: 0;
}

.in_wled_m {
  stop-color: var(--svg-color--655188, #655188);
  stop-opacity: 0;
}

.ius0mclhc {
  stop-color: var(--svg-color--9478ce, #9478CE);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j0qmv8b6d {
  stop-color: var(--svg-color--7a5fb3, #7A5FB3);
}

.j0x8wibsd {
  cx: 15.706px;
  cy: 13.219px;
  rx: 0.478px;
  ry: 0.242px;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.k-bk0xbne {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M12.496 6.719c.694-.736 2.008-.737 2.615-.627l.486 1.584c-.31-.048-.363-.002-.595.225c-.17 1.341-1.69 2.156-3.544 2.697c-.182-1.831.134-2.922 1.038-3.879");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k62cnfbxt {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m18.236 13.796l-.84 2.087a.662.662 0 0 0 .64.858h.965a.664.664 0 0 0 .64-.858l-.653-2.087c-.14-.462-.605-.462-.752 0");
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.khd7pkb9d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.5 4.782l.149 1.945");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.krd2fabda {
  stop-color: var(--svg-color--b7927f, #B7927F);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kybxapb2q {
  stop-color: var(--svg-color--8e675e, #8E675E);
  stop-opacity: 0;
}

.l57p2o49o {
  stop-color: var(--svg-color--97577d, #97577D);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lejfwxzry {
  stop-color: var(--svg-color--c8a48a, #C8A48A);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lnx1w7b3f {
  stop-color: var(--svg-color--9c745d, #9C745D);
  stop-opacity: 0;
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.lyo57mnwh {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m14.547 11.887l-.005.003a.33.33 0 0 1-.338-.564l.001-.002l.004-.002l.012-.006a3 3 0 0 1 .182-.095a4 4 0 0 1 .503-.198c.417-.133 1-.245 1.63-.134a.33.33 0 0 1-.114.648c-.49-.086-.96 0-1.316.113a3.4 3.4 0 0 0-.559.237");
}

.m2mta8b_j {
  stop-color: var(--svg-color--362659, #362659);
}

.m58fx9l3v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("M7.766 4.954L7.53 6.36");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mi0d6giae {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.514 3.466v3.088");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n66cvvb5y {
  d: path("M21.399 12.751a1.095 1.095 0 0 1 1.056 1.385h-2.117a1.1 1.1 0 0 1 1.06-1.384");
}

.ndb61xwjr {
  stop-color: var(--svg-color--97577d, #97577D);
  stop-opacity: 0;
}

.nmcs74byh {
  stop-color: var(--svg-color--9f6394, #9F6394);
}

.nrxnoi8to {
  stop-color: var(--svg-color--6b45ad, #6B45AD);
}

.nvs1l4bzh {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.653 12.418c.802 0 1.479.552 1.663 1.3a.336.336 0 0 1-.329.418H20.25a.283.283 0 0 1-.28-.334a1.716 1.716 0 0 1 1.684-1.384");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o6qx6mc1p {
  stop-color: var(--svg-color--7f4a33, #7F4A33);
  stop-opacity: 0;
}

.o8-s5pjlc {
  stop-color: var(--svg-color--6b45ad, #6B45AD);
  stop-opacity: 0;
}

.oct_5_7qz {
  cx: 15.706px;
  cy: 13.219px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.478px;
  ry: 0.242px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.og5w2nb6h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.819 7.57c.109-.062.617-.379.812-.758");
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.op15yplgp {
  stop-color: var(--svg-color--ad7b7c, #AD7B7C);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p80yl1i4o {
  fill: var(--svg-color--000, #000);
  d: path("M20.772 13.847c0-.349.278-.628.627-.628a.625.625 0 0 1 .558.917h-1.11a.57.57 0 0 1-.076-.29");
}

.phx3m2o6y {
  d: path("M7.06 13.514v5.172a2 2 0 0 0 1.38 1.901l4.183 1.363");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr1c_plua {
  stop-color: var(--svg-color--a97f72, #A97F72);
}

.pt7s1qkku {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m9.272 3.601l-.813 3.407");
}

.px0vdqe0d {
  stop-color: var(--svg-color--c09a87, #C09A87);
}

.qdtuxcc3i {
  stop-color: var(--svg-color--9e7963, #9E7963);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzl83lbyv {
  d: path("M21.318 12.983c.078.104-.085.231-.27.37c-.186.139-.323.236-.401.132s.009-.301.194-.44c.186-.139.4-.167.477-.062");
}

.r-j4-wrap {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.783 12.418c-.802 0-1.479.552-1.663 1.3a.336.336 0 0 0 .329.418h2.738c.174 0 .314-.16.28-.334a1.72 1.72 0 0 0-1.684-1.384");
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.rawj5ubfs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.169 6.04c.028.298.288 1.419.669 2.098");
}

.rnij5z0qd {
  stop-color: var(--svg-color--8969ba, #8969BA);
  stop-opacity: 0;
}

.rrtp5_b4o {
  d: path("M12.496 6.719c.694-.736 2.008-.737 2.615-.627l.486 1.584c-.31-.048-.363-.002-.595.225c-.17 1.341-1.69 2.156-3.544 2.697c-.182-1.831.134-2.922 1.038-3.879");
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rz1t4jbgv {
  stop-color: var(--svg-color--8b6ebc, #8B6EBC);
}

.s68njbc8b {
  stop-color: var(--svg-color--4f396f, #4F396F);
}

.sg-pxqbvz {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m21.343 9.25l-1.75.323a.845.845 0 1 1-.154-1.676h2.874c1.7 0 2.262 1.713 2.33 2.298a3.86 3.86 0 0 0-3.3-.944");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sy2nhlbqj {
  stop-color: var(--svg-color--7f4a33, #7F4A33);
}

.t-8ibsbxr {
  d: path("m18.249 13.626l-.653 2.087a.662.662 0 0 0 .64.859h.965a.664.664 0 0 0 .639-.859l-.653-2.087c-.14-.462-.792-.462-.938 0");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t6ahfk42q {
  stop-color: var(--svg-color--9c745d, #9C745D);
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tn-b1ujph {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M12.99 15.388a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tx_pqhb7h {
  stop-color: var(--svg-color--5e4490, #5E4490);
  stop-opacity: 0;
}

.txryfdvnp {
  d: path("M22.375 13.702a1.03 1.03 0 0 0-.284-.568l-.32.35l.145.28z");
}

.u-9w58unm {
  stop-color: var(--svg-color--745c92, #745C92);
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.uj0weyjko {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M5.986 6.604c-.13.165-.333.3-.519.4");
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.uw6orsblr {
  fill-rule: evenodd;
  d: path("M27.538 15.8a4 4 0 0 0 .397-1.751a4 4 0 0 0-.33-1.603h.007a4 4 0 0 0-.345-.63l-.002-.004a4 4 0 0 1-.646-2.173v-.013a4.05 4.05 0 0 0-4.05-4.05a.66.66 0 0 1-.56-.285a4.06 4.06 0 0 0-3.291-1.69c-1.354 0-2.56.671-3.292 1.69a.7.7 0 0 1-.56.285l-.104.002a4.05 4.05 0 0 0-3.945 4.048v.013c0 .77-.223 1.527-.646 2.173l-.003.005a4.05 4.05 0 0 0-.27 3.983a.63.63 0 0 1 0 .559a4 4 0 0 0-.398 1.727a3.944 3.944 0 0 0 3.95 3.95h10.535a3.944 3.944 0 0 0 3.95-3.95c0-.621-.149-1.205-.397-1.727a.63.63 0 0 1 0-.559m-15.05-3.28h-.015l1.472 2.891c.151 3.44 1.494 0 4.773 0s4.709 3.83 4.86.389l1.395-3.924c-.066-1.528-1.174-1.636-1.395-1.636h-3.952a4.74 4.74 0 0 1-3.915-2.054a.324.324 0 0 0-.567.063l-.1.238a2.83 2.83 0 0 1-1.523 1.54l-.063.025c-.29.15-.97.601-.995 1.766l.013.376z");
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vduttcjap {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m23.298 11.326l-.169.282za.33.33 0 0 1-.34.564l-.005-.003l-.026-.015l-.112-.056c-.1-.048-.244-.11-.42-.166c-.357-.114-.827-.2-1.316-.113a.33.33 0 1 1-.115-.648c.63-.111 1.213 0 1.63.134a4 4 0 0 1 .686.293l.012.006l.003.003z");
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vm40c2rnb {
  stop-color: var(--svg-color--655188, #655188);
}

.vt-rtgbrf {
  d: path("M24.643 16.045a1.975 1.975 0 1 0 0-3.95a1.975 1.975 0 0 0 0 3.95");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w6tqyubjs {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.445 11.157c-.396-.096-1.38-.048-2.038.423");
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.ww76qh22b {
  stop-color: var(--svg-color--c8a48a, #C8A48A);
}

.x21r1dbcr {
  d: path("M16.037 12.751a1.095 1.095 0 0 0-1.056 1.385h2.117q.038-.141.04-.29a1.103 1.103 0 0 0-1.101-1.095");
}

.x5paccbok {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m7.35 2.554l-.29 3.944");
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x97mw867e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.318 12.983c.078.104-.085.231-.27.37c-.186.139-.323.236-.401.132s.009-.301.194-.44c.186-.139.4-.167.477-.062");
}

.xgo-prp7n {
  stop-color: var(--svg-color--b7927f, #B7927F);
}

.xi0shyhbu {
  stop-color: var(--svg-color--9e7fdf, #9E7FDF);
  stop-opacity: 0;
}

.xkxmx1bvv {
  stop-color: var(--svg-color--8b6ebc, #8B6EBC);
  stop-opacity: 0;
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xrgpjcb6i {
  d: path("M18.718 23.692c-1.268 0-2.296-.986-2.296-2.2v-2.6c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.214-1.028 2.2-2.296 2.2");
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yjwsesbit {
  d: path("M17.977 4.507c-1.39-.307-2.638 1.08-2.782 1.594c1.29 4.352 4.557 4.113 7.782 3.755c1.93-.215 2.14.665 2.304 1.09c0-4.827-4.105-5.733-7.268-6.432z");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yy_71ub6o {
  stop-color: var(--svg-color--8967cb, #8967CB);
  stop-opacity: 0;
}

.zar_-tbdp {
  d: path("M19.683 20.586h.97c2.49 0 7.472 3.5 7.472 9H10.192v-3.5a.67.67 0 0 0-.414-.625l-3.073-1.375c-2.49-1-3.487-3.5-3.487-5.198v-5.287c0-.564.423-1.015.932-1.015h4.114c.517 0 .932.461.932 1.015v3.985c0 1.302.996 1.5.996 1.5l5.977 1.5z");
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

.zn-badfuu {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M20.12 13.371c.326-.573.82-1.026 1.887-1.026c.467 0 .917.13 1.317.453c.33.267.286.608.03.736l-.682.39c-.8-.26-1.685-.294-2.552-.553");
}

.zoqmhxs6u {
  d: path("m10.168 25.908l7.87-5.15l-1.614-.172h-.255l-5.977-1.5s-.996-.198-.996-1.5v-3.97l-.016-.034c0-.543-.415-.996-.935-.996H4.15c-.509 0-.932.451-.932 1.015v5.287c0 1.698.996 4.198 3.487 5.198l3.073 1.375a.66.66 0 0 1 .39.447");
}

</style>
