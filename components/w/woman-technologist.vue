<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iSFZDbe)" class="ax3t7fbst"/><path fill="url(#i7jw8Ac)" class="td7qnxbmr"/><path fill="url(#inT0zab)" class="c5jm6bc5b"/><path fill="url(#iRI2yhd)" class="g3ux3cbys"/><path fill="url(#ihnjaeb)" class="ny9_xhbeh"/><g filter="url(#i3eUHPe)"><path fill="url(#ihzU4KH)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iW1OlEd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#i2Zxfbb)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#i7DiQrb)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iBPC0jd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iZ16e2E)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iJeFSjb)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#ihCYYZd)" clip-rule="evenodd" class="bi4mzcbhr"/><path fill="url(#iusZTmb)" clip-rule="evenodd" class="bi4mzcbhr"/></g><g filter="url(#iCs6oqd)"><path fill="url(#iRp490c)" class="glnfjzbdq"/></g><g filter="url(#i0ABThc)"><path fill="url(#iOzzfne)" class="kmbgvqb8x"/></g><g filter="url(#iEBZXHe)"><path class="q0s_2fyfx"/><path fill="url(#iVHxNHM)" class="pp-_ab0pn"/></g><g filter="url(#iAc0uLc)"><path class="gj_g0ktqs"/><path fill="url(#iaivsfb)" class="o5u1ey-gn"/></g><g filter="url(#i3lWJce)"><path fill="url(#iyCLbWb)" class="j_stgnbgh"/><path fill="url(#iuemb4d)" class="j_stgnbgh"/><path fill="url(#ikjR1Vr)" class="j_stgnbgh"/><path fill="url(#iTLVmMb)" class="j_stgnbgh"/><path fill="url(#igdn6Ne)" class="j_stgnbgh"/><path fill="url(#ih1P3Gq)" class="j_stgnbgh"/><path fill="url(#i2Ran5b)" class="j_stgnbgh"/></g><path fill="url(#iANQZQd)" class="j_stgnbgh"/><g filter="url(#ideBb1d)"><path class="dvz4tkb2l"/></g><g filter="url(#iJvq1Ed)"><path fill="url(#i6c7imK)" class="vrruugv9e"/><path fill="url(#i4S1b9c)" class="vrruugv9e"/><path fill="url(#iEBnDCc)" class="vrruugv9e"/><path fill="url(#iRceNId)" class="vrruugv9e"/></g><path fill="url(#iKHByAe)" class="vrruugv9e"/><path fill="url(#i6sVqec)" class="vrruugv9e"/><path stroke="url(#ijcM7Sb)" class="ch76ezbzi"/><g filter="url(#iLt1eWd)"><path class="rntudfbte"/></g><g filter="url(#idEKNed)"><path class="c4isj006o"/></g><g filter="url(#iUAMPKX)"><path class="heq9ptbxa"/></g><g filter="url(#iDA2Vnd)"><path clip-rule="evenodd" class="idnnzlb6v"/></g><path class="uf5rerbdy"/><path fill="url(#iV4RUJc)" class="bzggbt_sv"/><path class="jo8lxfo6c"/><g filter="url(#iiWgWVc)"><path class="f5rqfpbzc"/><path fill="url(#iXEPr4b)" class="lxpg34q-q"/></g><g filter="url(#itzidDd)"><path fill="url(#iIvrZZc)" class="p2b69fj-n"/></g><path class="y03mew75m"/><path fill="url(#iArrE3b)" class="pndew4b9v"/><path class="ohwsnsbac"/><g filter="url(#i4RjDEc)"><path fill="url(#iu1LK7d)" class="qfqi3ccmh"/></g><g filter="url(#iiyIm1b)"><ellipse transform="rotate(-27.914 13.546 9.816)" class="sbdrz9sln"/><ellipse fill="url(#idxWCbe)" transform="rotate(-27.914 13.546 9.816)" class="busri7_ro"/></g><g filter="url(#iskzxVd)"><path class="nkojgrb_v"/></g><g filter="url(#i7IrGne)"><path class="fv3xufbxd"/></g><g filter="url(#iEqubMd)"><path fill="url(#iQMANon)" class="tjng2qbny"/><path fill="url(#iG6IC7d)" class="tjng2qbny"/></g><g filter="url(#imyuzze)"><path fill="url(#i0M0oke)" class="m8oq94drf"/><path fill="url(#itGxsJb)" class="m8oq94drf"/><path fill="url(#iWWygqc)" class="m8oq94drf"/></g><g filter="url(#i39YX1b)"><path stroke="url(#iSvvGPc)" class="q0zhnfbdv"/></g><g filter="url(#ipH7N2O)"><path fill="url(#iHXaVce)" class="jsqgobbht"/><path fill="url(#i2BUj5L)" class="jsqgobbht"/><path fill="url(#iqtSqJd)" class="jsqgobbht"/><path fill="url(#iNN1SaK)" class="jsqgobbht"/><path fill="url(#irzSjbb)" class="jsqgobbht"/><path fill="url(#ihI2zKe)" class="jsqgobbht"/></g><path fill="url(#ixwQhto)" class="ppwrykbzp"/><path fill="url(#i8N6NDd)" class="ppwrykbzp"/><path fill="url(#ilcEH9d)" class="ppwrykbzp"/><path fill="url(#iKDpaee)" class="ppwrykbzp"/><path fill="url(#i2FoUFP)" class="ppwrykbzp"/><path fill="url(#iWis4Qd)" class="w6exmsbsa"/><defs><radialGradient id="iSFZDbe" cx="0" cy="0" r="1" gradientTransform="matrix(2.78125 -.09375 .1236 3.66674 2.774 28.754)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="s-eg4sb7c"/><stop offset="1" class="o1jcigu0p"/></radialGradient><radialGradient id="i7jw8Ac" cx="0" cy="0" r="1" gradientTransform="rotate(151.68 11.043 17.873)scale(3.47887 3.35016)" gradientUnits="userSpaceOnUse"><stop class="lj4kaubvr"/><stop offset="1" class="ivc92ybcq"/></radialGradient><radialGradient id="iW1OlEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.45645 -2.68487 0 11.429 12.542)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="i2Zxfbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.9375 5.4375 -5.66415 -.97658 14.952 12.693)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="i7DiQrb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24075 1.61016 -1.56338 -1.2047 11.09 10.83)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="iBPC0jd" cx="0" cy="0" r="1" gradientTransform="matrix(-.46758 2.51377 -2.61762 -.4869 11.68 8.393)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="tgqxysbgm"/><stop offset="1" class="p1xq25bjq"/></radialGradient><radialGradient id="iZ16e2E" cx="0" cy="0" r="1" gradientTransform="rotate(62.605 3.58 12.086)scale(2.38097 4.53569)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iJeFSjb" cx="0" cy="0" r="1" gradientTransform="rotate(132.51 9.701 7.11)scale(1.63713 2.28786)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="ihCYYZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.16706 -4.01156 23.51 9.657)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iusZTmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00843 -1.37436 .45061 -.00276 13.295 5.84)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="sufhn4bec"/><stop offset="1" class="kpf8h5ohf"/></radialGradient><radialGradient id="iOzzfne" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.04 10.948)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iVHxNHM" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 40.314 -52.146)scale(1.30459)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iaivsfb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07411 0 0 -1.02745 11.334 10.509)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="iyCLbWb" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 8.335 7.055)scale(7.16175 9.58588)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="iuemb4d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10973 1.11592 -.94678 -1.78996 17.9 10.668)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="ikjR1Vr" cx="0" cy="0" r="1" gradientTransform="matrix(.8369 -4.04513 5.13253 1.06187 13.82 16.753)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="iTLVmMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.44059 -11.8177 0 15.738 9.487)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="ukj4rwtwn"/><stop offset=".952" class="j2bf1qocp"/></radialGradient><radialGradient id="igdn6Ne" cx="0" cy="0" r="1" gradientTransform="matrix(-5.42256 1.49953 -2.58173 -9.33598 16.627 11.627)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="ih1P3Gq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.301 9.552)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="i2Ran5b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.36 1.55865 0 14.082 9.64)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="iANQZQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.34695 0 0 -4.43421 21.095 11.04)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="i4S1b9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.69746 -2.44974 1.40177 -.3991 16.784 11.767)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="i6sVqec" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 6.316 8.314)scale(1.57489 2.10945)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="iV4RUJc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 9.912)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iXEPr4b" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.424 .601)scale(.37798 .52039)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iArrE3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 9.912)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="idxWCbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.00773 -.49366 .5934 -.0093 13.531 10.13)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQMANon" cx="0" cy="0" r="1" gradientTransform="rotate(129.554 5.805 4.907)scale(5.36951 2.34181)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="iG6IC7d" cx="0" cy="0" r="1" gradientTransform="rotate(144.458 5.915 4.158)scale(3.81321 1.88454)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="i0M0oke" cx="0" cy="0" r="1" gradientTransform="matrix(-2.18534 4.55504 -6.4674 -3.10282 17.791 2.383)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="itGxsJb" cx="0" cy="0" r="1" gradientTransform="rotate(105.909 7.882 8.804)scale(3.44004 7.20923)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="iWWygqc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.41682 -6.46744 5.78149 -3.05443 17.15 9.268)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><radialGradient id="i2BUj5L" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.59705 13.2772 0 17.243 31.067)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="o1-qqkidl"/><stop offset="1" class="q0dxfdmim"/></radialGradient><radialGradient id="ihI2zKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .4375 -.4057 -.72446 26.696 16.66)" gradientUnits="userSpaceOnUse"><stop class="nonrr22es"/><stop offset=".724" class="jehi2ihjx"/></radialGradient><radialGradient id="iWis4Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.0957 .08008 -.11939 -.14269 17.371 21.824)" gradientUnits="userSpaceOnUse"><stop class="a-otvg7dq"/><stop offset="1" class="t_w5hobcp"/></radialGradient><linearGradient id="inT0zab" x1="16" x2="16" y1="6.703" y2="34.611" gradientUnits="userSpaceOnUse"><stop class="zaeth0b6d"/><stop offset="1" class="vuad6pb7r"/></linearGradient><linearGradient id="iRI2yhd" x1="10.918" x2="1.428" y1="24.003" y2="24.044" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ihnjaeb" x1="22.998" x2="28.652" y1="24.02" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="vuad6pb7r"/><stop offset="1" class="zaeth0b6d"/></linearGradient><linearGradient id="ihzU4KH" x1="20.693" x2="13.452" y1="3.556" y2="16.999" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iRp490c" x1="9.705" x2="12.665" y1="10.596" y2="10.596" gradientUnits="userSpaceOnUse"><stop class="o-5xddb6x"/><stop offset="1" class="h11_utkon"/></linearGradient><linearGradient id="i6c7imK" x1="16" x2="16" y1="12.547" y2="9.865" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="iEBnDCc" x1="14.954" x2="15.808" y1="11.784" y2="11.889" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="iRceNId" x1="16" x2="16" y1="12.639" y2="12.028" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iKHByAe" x1="16.078" x2="16.078" y1="12.612" y2="12.473" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="ijcM7Sb" x1="15.271" x2="15.724" y1="14.116" y2="13.244" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="iIvrZZc" x1="18.96" x2="18.646" y1="9.965" y2="10.158" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iu1LK7d" x1="14.561" x2="14.248" y1="9.965" y2="10.158" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSvvGPc" x1="13.109" x2="13.653" y1="4.31" y2="5.584" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="iHXaVce" x1="7.493" x2="11.284" y1="19.754" y2="30.805" gradientUnits="userSpaceOnUse"><stop class="ux-m5bn7d"/><stop offset="1" class="l294t3zvi"/></linearGradient><linearGradient id="iqtSqJd" x1="16" x2="16" y1="16.02" y2="17.379" gradientUnits="userSpaceOnUse"><stop class="dmu1fh1sq"/><stop offset=".268" class="gzfhb8b1n"/><stop offset=".863" class="szjcm-w7x"/></linearGradient><linearGradient id="iNN1SaK" x1="5" x2="6.055" y1="24.254" y2="24.254" gradientUnits="userSpaceOnUse"><stop class="a61ap5b7j"/><stop offset="1" class="p9llu9bpa"/></linearGradient><linearGradient id="irzSjbb" x1="27" x2="25.524" y1="25.192" y2="25.192" gradientUnits="userSpaceOnUse"><stop offset=".174" class="yr342ibfl"/><stop offset="1" class="d9m_15bme"/></linearGradient><linearGradient id="ixwQhto" x1="17.977" x2="13.911" y1="23.099" y2="23.099" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qufyc6r7b"/><stop offset=".13" class="xqmtwwbyq"/><stop offset=".165" class="k71v6_7um"/><stop offset="1" class="uem0lbchq"/></linearGradient><linearGradient id="i8N6NDd" x1="15.999" x2="15.999" y1="21.641" y2="23.196" gradientUnits="userSpaceOnUse"><stop class="w9bfwpbnq"/><stop offset="1" class="zt_ualb3u"/></linearGradient><linearGradient id="ilcEH9d" x1="15.999" x2="15.999" y1="21.641" y2="24.557" gradientUnits="userSpaceOnUse"><stop class="l17xqebtl"/><stop offset=".037" class="r1d3vkbxd"/><stop offset=".058" class="bowxt9bwr"/><stop offset=".097" class="g48yfbn9k"/></linearGradient><linearGradient id="iKDpaee" x1="14.444" x2="15.02" y1="23.122" y2="23.122" gradientUnits="userSpaceOnUse"><stop offset=".086" class="v1n2dlbml"/><stop offset=".663" class="ohv650iba"/></linearGradient><linearGradient id="i2FoUFP" x1="15.999" x2="15.999" y1="24.842" y2="24.168" gradientUnits="userSpaceOnUse"><stop offset=".507" class="qqk6g6zlh"/><stop offset=".736" class="auud8yb7i"/></linearGradient><filter id="i3eUHPe" width="15.268" height="15.268" x="8.491" y="1.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.537255 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_727"/></filter><filter id="iCs6oqd" width="3.318" height="3.218" x="9.705" y="8.899" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.501961 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_727"/></filter><filter id="i0ABThc" width="3.218" height="3.468" x="19.218" y="8.649" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_727"/></filter><filter id="iEBZXHe" width="3.148" height="3.148" x="19.253" y="8.935" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".25"/></filter><filter id="iAc0uLc" width="2.648" height="2.648" x="10.009" y="9.185" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".125"/></filter><filter id="i3lWJce" width="10.191" height="11.277" x="10.905" y="5.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_727"/></filter><filter id="ideBb1d" width="2.877" height="3.682" x="14.399" y="9.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".25"/></filter><filter id="iJvq1Ed" width="2.377" height="3.182" x="14.811" y="9.615" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".125"/></filter><filter id="iLt1eWd" width="3.001" height="1.285" x="16.942" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_727"/></filter><filter id="idEKNed" width="3.001" height="1.285" x="12.057" y="9.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_727"/></filter><filter id="iUAMPKX" width="2.453" height="1.091" x="12.192" y="7.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_727"/></filter><filter id="iDA2Vnd" width="2.453" height="1.091" x="17.609" y="7.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_727"/></filter><filter id="iiWgWVc" width=".786" height=".696" x="17.448" y="9.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".05"/></filter><filter id="itzidDd" width=".891" height=".913" x="18.288" y="9.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".1"/></filter><filter id="i4RjDEc" width=".986" height="1.04" x="13.845" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".1"/></filter><filter id="iiyIm1b" width=".912" height=".704" x="13.09" y="9.463" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".05"/></filter><filter id="iskzxVd" width="2.661" height="1.378" x="17.439" y="7.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".2"/></filter><filter id="i7IrGne" width="2.661" height="1.378" x="11.988" y="7.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".2"/></filter><filter id="iEqubMd" width="4.985" height="5.214" x="9.292" y="3.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".375"/></filter><filter id="imyuzze" width="8.914" height="5.78" x="12.683" y="2.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".125"/></filter><filter id="i39YX1b" width="1.145" height="2.31" x="12.809" y="3.667" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3_727" stdDeviation=".125"/></filter><filter id="ipH7N2O" width="22" height="14.1" x="5" y="16.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.670588 0 0 0 0 0.682353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3_727"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-technologist" /></template>
<style>
.a-otvg7dq {
  stop-color: var(--svg-color--806b97, #806B97);
}

.a61ap5b7j {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.auud8yb7i {
  stop-color: var(--svg-color--4a3261, #4A3261);
  stop-opacity: 0;
}

.ax3t7fbst {
  d: path("M8.329 30.02q.004-.082.004-.163a3.138 3.138 0 1 0-6.271.162z");
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.bi4mzcbhr {
  fill-rule: evenodd;
  d: path("M23.185 11.918c.213-.435.324-.92.324-1.427c0-.467-.096-.905-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.003a3.24 3.24 0 0 1-.527-1.771v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.232A3.3 3.3 0 0 0 16 1.98a3.3 3.3 0 0 0-2.682 1.377a.56.56 0 0 1-.455.233h-.085a3.3 3.3 0 0 0-3.214 3.3v.01a3.24 3.24 0 0 1-.527 1.77l-.002.004a3.3 3.3 0 0 0-.22 3.245c.07.142.07.314 0 .456A3.213 3.213 0 0 0 11.709 17h8.582a3.213 3.213 0 0 0 3.218-3.219c0-.506-.121-.981-.324-1.406a.51.51 0 0 1 0-.456m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.673a.264.264 0 0 0-.461.05l-.082.195a2.3 2.3 0 0 1-1.292 1.275c-.236.122-.79.49-.81 1.439l.01.306z");
}

.bowxt9bwr {
  stop-color: var(--svg-color--6f5783, #6F5783);
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.busri7_ro {
  cx: 13.546px;
  cy: 9.816px;
  rx: 0.389px;
  ry: 0.197px;
}

.bzggbt_sv {
  d: path("M18.184 9.435a.892.892 0 0 1 .86 1.127H17.32a.896.896 0 0 1 .864-1.128");
}

.c4isj006o {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.858 9.94c-.265-.467-.669-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.269.217-.233.495-.025.599l.556.317c.652-.21 1.373-.239 2.08-.45");
}

.c5jm6bc5b {
  d: path("M16 15.52c-6.07 0-11 4.92-11 11v3.5h22v-3.5c0-6.08-4.93-11-11-11");
}

.ch76ezbzi {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.602 13.031a.204.204 0 0 0-.248.043a.196.196 0 0 0-.02.248a1.982 1.982 0 0 0 3.333 0a.2.2 0 0 0-.022-.25a.205.205 0 0 0-.246-.041A3 3 0 0 1 16 13.37a3 3 0 0 1-1.398-.339Z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.d9m_15bme {
  stop-color: var(--svg-color--a191b5, #A191B5);
  stop-opacity: 0;
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dmu1fh1sq {
  stop-color: var(--svg-color--beb0b0, #BEB0B0);
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.dvz4tkb2l {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.607 10.286l-.683 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.377-.493-.377-.613 0");
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.f5rqfpbzc {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.118 9.623c.063.085-.07.189-.22.302c-.151.113-.263.192-.327.107c-.063-.085.007-.245.159-.358c.15-.113.324-.136.388-.05");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.ft5dv1b6b {
  fill: none;
}

.fv3xufbxd {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.149 8.136c-.323-.079-1.125-.04-1.661.344");
}

.g3ux3cbys {
  d: path("M8.98 18.02a10.99 10.99 0 0 0-3.97 8.5l.02 3.5l4-.02z");
}

.g48yfbn9k {
  stop-color: var(--svg-color--5f447b, #5F447B);
  stop-opacity: 0;
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gj_g0ktqs {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.334 11.583a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.glnfjzbdq {
  d: path("M11.314 12.118a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gzfhb8b1n {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
}

.h11_utkon {
  stop-color: var(--svg-color--b96201, #B96201);
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.heq9ptbxa {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.602 8.73l-.004.003a.268.268 0 0 1-.276-.46h.002l.003-.003l.01-.005a2 2 0 0 1 .148-.077a3 3 0 0 1 .41-.162c.34-.108.815-.2 1.328-.109a.268.268 0 1 1-.093.528a2.3 2.3 0 0 0-1.072.092a3 3 0 0 0-.434.182z");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.idnnzlb6v {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.732 8.273l-.138.23za.268.268 0 0 1-.275.46l-.005-.002a1 1 0 0 0-.113-.059a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988.001 1.328.11a3.3 3.3 0 0 1 .559.238l.009.005z");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.ivc92ybcq {
  stop-color: var(--svg-color--f8c743, #F8C743);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j_stgnbgh {
  d: path("M10.913 9.246h.012l-.01-.266l-.01-.306c.02-.949.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.194a.264.264 0 0 1 .461-.05a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.803-2.312 4.684-4.984 4.684c-2.671 0-4.86-1.882-4.983-4.684z");
}

.j2bf1qocp {
  stop-color: var(--svg-color--cb7b39, #CB7B39);
}

.jehi2ihjx {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
  stop-opacity: 0;
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jo8lxfo6c {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.327c0-.284.227-.511.511-.511a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.235");
}

.jsqgobbht {
  d: path("M26.03 16.02H5.97a.97.97 0 0 0-.97.97v13.03h22V16.99a.97.97 0 0 0-.97-.97");
}

.k71v6_7um {
  stop-color: var(--svg-color--51366c, #51366C);
}

.kmbgvqb8x {
  d: path("M20.827 12.118a1.61 1.61 0 1 0 0-3.219a1.61 1.61 0 0 0 0 3.219");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kpf8h5ohf {
  stop-color: var(--svg-color--db6009, #DB6009);
  stop-opacity: 0;
}

.l17xqebtl {
  stop-color: var(--svg-color--594170, #594170);
}

.l294t3zvi {
  stop-color: var(--svg-color--847498, #847498);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj4kaubvr {
  stop-color: var(--svg-color--ffeb48, #FFEB48);
}

.lxpg34q-q {
  d: path("M18.118 9.623c.063.085-.07.189-.22.302c-.151.113-.263.192-.327.107c-.063-.085.007-.245.159-.358c.15-.113.324-.136.388-.05");
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.m8oq94drf {
  d: path("M15.397 2.718c-1.133-.25-2.347.955-2.464 1.374c1.542 3.62 3.91 3.276 6.537 2.984c1.572-.175 1.743.542 1.877.888c-.436-4.056-3.37-4.676-5.95-5.246");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nkojgrb_v {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.94 8.136c.322-.079 1.124-.04 1.66.344");
}

.nonrr22es {
  stop-color: var(--svg-color--e5dff1, #E5DFF1);
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.ny9_xhbeh {
  d: path("M23 18.03v11.98h4v-3.5c0-3.41-1.56-6.46-4-8.48");
}

.o-5xddb6x {
  stop-color: var(--svg-color--e79b27, #E79B27);
}

.o1-qqkidl {
  stop-color: var(--svg-color--78698c, #78698C);
}

.o1jcigu0p {
  stop-color: var(--svg-color--eba02a, #EBA02A);
}

.o5u1ey-gn {
  d: path("M11.334 11.583a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohv650iba {
  stop-color: var(--svg-color--52376c, #52376C);
  stop-opacity: 0;
}

.ohwsnsbac {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.327a.51.51 0 0 0-.511-.511a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .061-.235");
}

.p1xq25bjq {
  stop-color: var(--svg-color--d76a18, #D76A18);
  stop-opacity: 0;
}

.p2b69fj-n {
  d: path("M18.979 10.209a.84.84 0 0 0-.232-.462l-.26.285l.118.228z");
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p9llu9bpa {
  stop-color: var(--svg-color--9f93b2, #9F93B2);
  stop-opacity: 0;
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pndew4b9v {
  d: path("M13.816 9.435a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.pp-_ab0pn {
  d: path("M20.827 11.583a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.ppwrykbzp {
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.q0dxfdmim {
  stop-color: var(--svg-color--7a6b8e, #7A6B8E);
  stop-opacity: 0;
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q0s_2fyfx {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.827 11.583a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.q0zhnfbdv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.109 3.967c.023.243.234 1.156.544 1.71");
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qfqi3ccmh {
  d: path("M14.63 10.221c0-.288-.234-.48-.297-.538l-.288.279l.177.36z");
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qqk6g6zlh {
  stop-color: var(--svg-color--3d2555, #3D2555);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qufyc6r7b {
  stop-color: var(--svg-color--56416b, #56416B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r1d3vkbxd {
  stop-color: var(--svg-color--6d5686, #6D5686);
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rntudfbte {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.142 9.94c.265-.467.669-.836 1.537-.836c.38 0 .747.105 1.073.369c.27.217.233.495.025.599l-.556.317c-.652-.21-1.373-.239-2.079-.45");
}

.s-eg4sb7c {
  stop-color: var(--svg-color--fdc64d, #FDC64D);
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.sbdrz9sln {
  cx: 13.546px;
  cy: 9.816px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.sufhn4bec {
  stop-color: var(--svg-color--db6009, #DB6009);
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.szjcm-w7x {
  stop-color: var(--svg-color--beb7c7, #BEB7C7);
  stop-opacity: 0;
}

.t_w5hobcp {
  stop-color: var(--svg-color--8d78a4, #8D78A4);
  stop-opacity: 0;
}

.td7qnxbmr {
  d: path("M29.938 30.02q.005-.082.005-.163a3.138 3.138 0 1 0-6.272.162z");
}

.tgqxysbgm {
  stop-color: var(--svg-color--d76a18, #D76A18);
}

.tjng2qbny {
  d: path("M11.106 4.495c.62-.554 1.517-.56 2.02-.47l.402 1.29c-.257-.038-.486.051-.679.236c-.456 1.26-2.023 1.955-2.749 2.145c-.15-1.492-.067-2.246 1.006-3.201");
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.uem0lbchq {
  stop-color: var(--svg-color--4f3568, #4F3568);
}

.uf5rerbdy {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.163c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.ukj4rwtwn {
  stop-color: var(--svg-color--e0942e, #E0942E);
  stop-opacity: 0;
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.ux-m5bn7d {
  stop-color: var(--svg-color--ab9cbe, #AB9CBE);
}

.v1n2dlbml {
  stop-color: var(--svg-color--3b2b50, #3B2B50);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vrruugv9e {
  d: path("m15.618 10.147l-.532 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.376-.646-.376-.765 0");
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vuad6pb7r {
  stop-color: var(--svg-color--1c1c1c, #1C1C1C);
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w6exmsbsa {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.444 21.89a.25.25 0 0 1 .25-.25h2.61a.25.25 0 0 1 .25.25v2.417a.25.25 0 0 1-.25.25h-2.61a.25.25 0 0 1-.25-.25z");
}

.w9bfwpbnq {
  stop-color: var(--svg-color--60407f, #60407F);
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.xqmtwwbyq {
  stop-color: var(--svg-color--614c77, #614C77);
}

.y03mew75m {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.609 9.163c-.653 0-1.205.45-1.355 1.058a.275.275 0 0 0 .268.341h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.371-1.127");
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.yr342ibfl {
  stop-color: var(--svg-color--bab9c0, #BAB9C0);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zt_ualb3u {
  stop-color: var(--svg-color--543870, #543870);
  stop-opacity: 0;
}

</style>
