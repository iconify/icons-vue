<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iRQkgpd)" class="sem6ntf8z"/><circle fill="url(#isZNEwb)" class="sem6ntf8z"/><circle fill="url(#iknmPZc)" class="l-n61r67s"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.12)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.12)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.323)" class="n5l_opbqq"/><g filter="url(#iQZc34d)"><path fill="url(#iZ7ttsd)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#iFlilae)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#iYqBgLU)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#i7Yb07c)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#isLgaKe)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#iWXNNAb)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#isD5Sse)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#ifYSuxd)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#ij33iPd)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#iTcHl4j)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#i7NYxVc)" clip-rule="evenodd" class="k02lm1bfz"/><path fill="url(#ik8ewte)" clip-rule="evenodd" class="k02lm1bfz"/></g><path fill="url(#iJ9CSXc)" class="s2ztaubvo"/><path fill="url(#iSqxQoe)" class="s2ztaubvo"/><path fill="url(#iPBhU4d)" class="s2ztaubvo"/><path fill="url(#iQVCEIb)" class="rw2ievmrq"/><path fill="url(#iuIsCHe)" class="rw2ievmrq"/><path class="qbry5nb_d"/><path fill="url(#ivjJeOd)" class="x2wiwlbfv"/><path fill="url(#iswaBze)" class="x2wiwlbfv"/><path fill="url(#iFLr36G)" class="x2wiwlbfv"/><path fill="url(#i8v6Dsb)" class="x2wiwlbfv"/><path fill="url(#iPArKsd)" class="x2wiwlbfv"/><path fill="url(#iTyEP8d)" class="x2wiwlbfv"/><path class="h17aqmc7c"/><path fill="url(#iyFAwId)" class="euze1ubdn"/><path fill="url(#ipHilRd)" class="euze1ubdn"/><path fill="url(#iZ4UqEd)" class="euze1ubdn"/><g filter="url(#ivXFltb)"><path fill="url(#i5MjWMO)" class="s4bid24aq"/><path fill="url(#iMfS0Fb)" class="s4bid24aq"/><path fill="url(#iYht4Wb)" class="s4bid24aq"/></g><path class="cr6h_c1qd"/><g filter="url(#iGBmmAd)"><path class="e2_qzobga"/></g><path fill="url(#iL36o8d)" class="xvf28obeq"/><path fill="url(#i1fAkod)" class="ns5jhvbjf"/><g filter="url(#iZju96c)"><path fill="url(#ibm7STv)" class="qgx5q8byi"/></g><path fill="url(#ibm8unc)" class="qgx5q8byi"/><g filter="url(#iQeQaFk)"><path fill="url(#iKgXPKE)" class="y8qx7dbfv"/><path fill="url(#iQSgM3r)" class="y8qx7dbfv"/></g><g filter="url(#i9M26Wb)"><path class="iky6zuwiy"/><path fill="url(#iwgSSyd)" class="sr-221a-o"/></g><g filter="url(#iosU0bd)"><path class="o1tsckbsu"/><path fill="url(#inxG48d)" class="yf2be6b7n"/></g><g filter="url(#idL84xc)"><path fill="url(#itfMVQb)" class="etuvdbcrg"/><path fill="url(#idDjGHb)" class="etuvdbcrg"/><path fill="url(#i4KIOxe)" class="etuvdbcrg"/><path fill="url(#iMLDVng)" class="etuvdbcrg"/><path fill="url(#i711gle)" class="etuvdbcrg"/><path fill="url(#idpcdqc)" class="etuvdbcrg"/><path fill="url(#iwvR7fd)" class="etuvdbcrg"/><path fill="url(#iK6DeLe)" class="etuvdbcrg"/></g><path fill="url(#itieWUd)" class="etuvdbcrg"/><g filter="url(#iSdcDnJ)"><path class="uoi1brb7t"/></g><g filter="url(#ifhlvXS)"><path class="t3jo2gbov"/><path fill="url(#i8O8Dmb)" class="koms7kb5h"/><path fill="url(#ibzHQKe)" class="koms7kb5h"/><path fill="url(#i9bbGfI)" class="koms7kb5h"/><path fill="url(#iArDfEb)" class="koms7kb5h"/></g><g filter="url(#ipDHpWd)"><path stroke="url(#iv4slhd)" class="szk7albek"/></g><path class="yriwpzb7a"/><g filter="url(#i6cR0Dd)"><path class="m5prodbki"/></g><g filter="url(#i7hp2Yp)"><path class="wnjhqclnr"/></g><g filter="url(#isg4ibc)"><path class="j9f40ss8t"/></g><g filter="url(#i1Bi4Uc)"><path clip-rule="evenodd" class="tan30xb_g"/></g><path class="e4nsc89bw"/><path fill="url(#is8zkNb)" class="qpg180b3w"/><path class="l71ib0olo"/><g filter="url(#iWvkF1b)"><path class="miuob-dnm"/><path fill="url(#i9vEo0c)" class="wmoe-d3ab"/></g><g filter="url(#iF27R3b)"><path fill="url(#iwCXkYQ)" class="z2_09-bfu"/></g><path class="r4n8i0bee"/><path fill="url(#iuJa7Rb)" class="ifq4m0b_p"/><path class="awqy5eb3l"/><g filter="url(#iWUWGdc)"><path fill="url(#i5Yolfc)" class="nu--26b9x"/></g><g filter="url(#iDczRYd)"><ellipse transform="rotate(-27.914 13.461 9.98)" class="ljtsggi4h"/><ellipse fill="url(#iHPIDae)" transform="rotate(-27.914 13.461 9.98)" class="qxmjg8p4i"/></g><g filter="url(#iEFpsGe)"><path class="md6qzfbic"/></g><g filter="url(#iZm2rUm)"><path class="kb-1tmb8e"/></g><g filter="url(#i9jfiye)"><path class="prx855tol"/><path fill="url(#ijuZVFd)" class="eorumbbww"/><path fill="url(#ig3aCVd)" class="eorumbbww"/></g><g filter="url(#iXGyhIj)"><path class="tp9z2fb1u"/><path fill="url(#idFhV0b)" class="erhusabwh"/><path fill="url(#ibFQG1O)" class="erhusabwh"/></g><g filter="url(#iXGWHbd)"><path stroke="url(#iIHLVkd)" class="gxgnakb2c"/></g><g filter="url(#i6IIYeb)"><path class="j4puavbfr"/></g><defs><radialGradient id="iRQkgpd" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.284)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="isZNEwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.784)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="iknmPZc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.223)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="iFlilae" cx="0" cy="0" r="1" gradientTransform="matrix(-.60753 4.59028 -5.7342 -.75893 15.628 13.195)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iYqBgLU" cx="0" cy="0" r="1" gradientTransform="matrix(-2.90275 1.95764 -2.57218 -3.81398 12.793 13.466)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="i7Yb07c" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.834 8.182)scale(2.16698 1.66394)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="isLgaKe" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.27 7.657)scale(2.492 1.7554)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iWXNNAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.38384 2.63266 -3.65454 1.92098 12.387 2.564)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="isD5Sse" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45125 1.45135 -2.02824 -2.0281 21.804 4.656)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="ifYSuxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85628 .54004 -1.1262 -3.87114 23.492 9.82)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="ij33iPd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.83509 .70881 -.90292 -3.61148 22.884 13.263)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="iTcHl4j" cx="0" cy="0" r="1" gradientTransform="matrix(-.91063 -2.6684 2.11055 -.72026 20.696 7.37)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="i7NYxVc" cx="0" cy="0" r="1" gradientTransform="matrix(1.51421 .15883 -.25735 2.45346 9.747 9.784)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="ik8ewte" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 14.186 -3.857)scale(3.82387 1.38011)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="iJ9CSXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.534)" gradientUnits="userSpaceOnUse"><stop class="ttp7yqb-m"/><stop offset="1" class="jletv-brl"/></radialGradient><radialGradient id="iQVCEIb" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.274)" gradientUnits="userSpaceOnUse"><stop class="wv2o2nbhk"/><stop offset="1" class="n44b27bdp"/></radialGradient><radialGradient id="ivjJeOd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.346)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="epu6iq_fg"/><stop offset="1" class="q8d1l4bok"/></radialGradient><radialGradient id="iFLr36G" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.917)" gradientUnits="userSpaceOnUse"><stop class="x37sucbkr"/><stop offset="1" class="k796fybnd"/></radialGradient><radialGradient id="iPArKsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.534)" gradientUnits="userSpaceOnUse"><stop class="bp-uy2zsn"/><stop offset="1" class="dfpk_zbbl"/></radialGradient><radialGradient id="iTyEP8d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.47)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="jhdqd89ez"/><stop offset="1" class="tbqxjbcmi"/></radialGradient><radialGradient id="ipHilRd" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.284)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="x4p5bn7mz"/><stop offset="1" class="rz_1qnb6a"/></radialGradient><radialGradient id="iZ4UqEd" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.506 18.271)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="tqo-vnfob"/><stop offset="1" class="fqnn-rb2e"/></radialGradient><radialGradient id="iMfS0Fb" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.92625 -2.40786 2.26568 13.158 16.127)" gradientUnits="userSpaceOnUse"><stop offset=".047" class="e9j5vvbvj"/><stop offset="1" class="l0nudab1i"/></radialGradient><radialGradient id="iYht4Wb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.31547 -.76307 0 16.64 15.044)" gradientUnits="userSpaceOnUse"><stop class="lj_bse8ns"/><stop offset="1" class="ma74w36yx"/></radialGradient><radialGradient id="ibm8unc" cx="0" cy="0" r="1" gradientTransform="matrix(-.65817 -1.2117 1.37302 -.7458 10.818 12.298)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iKgXPKE" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 35.667 -40.602)scale(2.75284 3.36109)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iQSgM3r" cx="0" cy="0" r="1" gradientTransform="matrix(1.21508 0 0 .52316 20.91 8.96)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iwgSSyd" cx="0" cy="0" r="1" gradientTransform="matrix(1.52023 -.11308 .0884 1.1884 20.353 10.79)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="inxG48d" cx="0" cy="0" r="1" gradientTransform="rotate(-180 5.65 5.339)scale(1.06319)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="itfMVQb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.5481 3.01954 -4.0416 -8.76451 18.81 10.136)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="idDjGHb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1952 .96596 -.67268 -1.5287 17.915 10.996)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="i4KIOxe" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 18.398 -1.15)scale(4.16278 5.2818)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="iMLDVng" cx="0" cy="0" r="1" gradientTransform="rotate(99.884 4.395 11.99)scale(7.53551 9.41929)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="fa0q4x0wh"/><stop offset=".955" class="vfgk4hb_x"/></radialGradient><radialGradient id="i711gle" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.3 6.802)scale(7.08556 12.1992)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="idpcdqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15865 1.42198 0 18.248 9.715)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iwvR7fd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.3215 1.51453 0 13.84 9.485)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="iK6DeLe" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 5.834 10.327)scale(3.36489 2.69247)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="itieWUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29408 0 0 -6.48969 21.061 11.213)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="i8O8Dmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45866 -2.058 .63426 -.14136 16.72 11.944)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iArDfEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.78474 0 0 -.21939 16.48 12.158)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="is8zkNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81687 -1.29932 0 18.128 10.076)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i9vEo0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.2335 -.3009 .41427 -.32148 17.898 10.161)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iuJa7Rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81688 -1.29933 0 13.734 10.076)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iHPIDae" cx="0" cy="0" r="1" gradientTransform="matrix(-.00779 -.49744 .59795 -.00936 13.445 10.297)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijuZVFd" cx="0" cy="0" r="1" gradientTransform="matrix(1.27067 -2.7743 1.41926 .65004 10.234 7.941)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="ig3aCVd" cx="0" cy="0" r="1" gradientTransform="matrix(1.1574 -1.98876 1.0677 .62136 11.954 6.954)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="idFhV0b" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.08 6.962)scale(4.90626 8.02145)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="ibFQG1O" cx="0" cy="0" r="1" gradientTransform="matrix(-.21177 1.37656 -2.96159 -.45562 16.143 3.07)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><filter id="iQZc34d" width="15.371" height="15.871" x="8.371" y="1.341" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/></filter><filter id="ivXFltb" width="6.906" height="12.039" x="12.293" y="15.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.329412 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/></filter><filter id="iGBmmAd" width="3.076" height="1.977" x="15.245" y="17.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".3"/></filter><filter id="iZju96c" width="3.39" height="3.24" x="9.594" y="9.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/></filter><filter id="iQeQaFk" width="3.24" height="3.49" x="19.171" y="8.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/></filter><filter id="i9M26Wb" width="3.163" height="3.163" x="19.21" y="9.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".25"/></filter><filter id="iosU0bd" width="2.863" height="2.863" x="9.801" y="9.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".175"/></filter><filter id="idL84xc" width="10.261" height="11.201" x="10.801" y="5.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/></filter><filter id="iSdcDnJ" width="2.89" height="3.7" x="14.322" y="9.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".25"/></filter><filter id="ifhlvXS" width="2.39" height="3.2" x="14.736" y="9.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".125"/></filter><filter id="ipDHpWd" width="3.725" height="1.534" x="14.069" y="13.043" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".05"/></filter><filter id="i6cR0Dd" width="3.021" height="1.294" x="16.881" y="9.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0705882 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/></filter><filter id="i7hp2Yp" width="3.021" height="1.294" x="11.961" y="9.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/></filter><filter id="isg4ibc" width="2.468" height="1.097" x="12.097" y="7.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/></filter><filter id="i1Bi4Uc" width="2.468" height="1.097" x="17.551" y="7.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/></filter><filter id="iWvkF1b" width=".791" height=".7" x="17.39" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".05"/></filter><filter id="iF27R3b" width=".895" height=".917" x="18.236" y="9.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".1"/></filter><filter id="iWUWGdc" width=".99" height="1.045" x="13.763" y="9.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".1"/></filter><filter id="iDczRYd" width=".918" height=".708" x="13.002" y="9.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".05"/></filter><filter id="iEFpsGe" width="2.272" height=".98" x="17.584" y="7.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".1"/></filter><filter id="iZm2rUm" width="2.272" height=".98" x="12.095" y="7.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".1"/></filter><filter id="i9jfiye" width="4.335" height="4.639" x="9.536" y="3.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/><feGaussianBlur result="effect2_foregroundBlur_4002_786" stdDeviation=".2"/></filter><filter id="iXGyhIj" width="8.824" height="5.818" x="12.741" y="2.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_786"/><feGaussianBlur result="effect2_foregroundBlur_4002_786" stdDeviation=".125"/></filter><filter id="iXGWHbd" width="1.149" height="2.321" x="12.72" y="3.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".1"/></filter><filter id="i6IIYeb" width="6.461" height="3.385" x="15.351" y="4.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_786" stdDeviation=".375"/></filter><linearGradient id="iZ7ttsd" x1="20.657" x2="14.48" y1="3.677" y2="14.512" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iSqxQoe" x1="24.158" x2="24.189" y1="30.284" y2="26.628" gradientUnits="userSpaceOnUse"><stop offset=".078" class="y41hsabjm"/><stop offset="1" class="y-a_999zn"/></linearGradient><linearGradient id="iPBhU4d" x1="18.12" x2="19.472" y1="27.72" y2="28.106" gradientUnits="userSpaceOnUse"><stop class="mbuex5b5r"/><stop offset="1" class="ozroxmy8l"/></linearGradient><linearGradient id="iuIsCHe" x1="13.658" x2="12.158" y1="28.69" y2="29.221" gradientUnits="userSpaceOnUse"><stop class="g82zxu-vf"/><stop offset="1" class="sv9br1byn"/></linearGradient><linearGradient id="iswaBze" x1="12.315" x2="13.69" y1="27.346" y2="26.784" gradientUnits="userSpaceOnUse"><stop offset=".223" class="zantcf-1d"/><stop offset="1" class="tkat5cdin"/></linearGradient><linearGradient id="i8v6Dsb" x1="15.627" x2="14.221" y1="30.128" y2="29.44" gradientUnits="userSpaceOnUse"><stop offset=".208" class="roh2cebgd"/><stop offset="1" class="u44j7rbwl"/></linearGradient><linearGradient id="iyFAwId" x1="16.002" x2="18.033" y1="24.784" y2="25.69" gradientUnits="userSpaceOnUse"><stop class="z0qi4zb3s"/><stop offset="1" class="nh4l3fbho"/></linearGradient><linearGradient id="i5MjWMO" x1="16.366" x2="16.366" y1="24.868" y2="14.382" gradientUnits="userSpaceOnUse"><stop class="on-ymlb8c"/><stop offset="1" class="czjae1pgq"/></linearGradient><linearGradient id="iL36o8d" x1="8.677" x2="23.191" y1="15.515" y2="15.515" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="i1fAkod" x1="8.677" x2="23.191" y1="15.485" y2="15.485" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ibm7STv" x1="9.594" x2="11.464" y1="10.765" y2="10.765" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="ibzHQKe" x1="14.986" x2="15.931" y1="12.018" y2="12.018" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="i9bbGfI" x1="15.931" x2="15.931" y1="12.73" y2="12.098" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iv4slhd" x1="14.86" x2="15.324" y1="14.242" y2="13.525" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iwCXkYQ" x1="18.912" x2="18.596" y1="10.131" y2="10.325" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i5Yolfc" x1="14.483" x2="14.167" y1="10.131" y2="10.325" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIHLVkd" x1="12.802" x2="13.294" y1="3.678" y2="4.952" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-in-steamy-room-medium" /></template>
<style>
.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.awqy5eb3l {
  fill: var(--svg-color--000, #000);
  d: path("M14.247 10.495a.51.51 0 0 0-.515-.515a.513.513 0 0 0-.457.752h.91a.5.5 0 0 0 .062-.237");
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bp-uy2zsn {
  stop-color: var(--svg-color--442d6d, #442D6D);
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

.cr6h_c1qd {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 23.971h3.298a5.94 5.94 0 0 1 5.937 5.938H1.971zm28.06 0h-3.298a5.937 5.937 0 0 0-5.937 5.938h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.czjae1pgq {
  stop-color: var(--svg-color--a77c63, #A77C63);
}

.dfpk_zbbl {
  stop-color: var(--svg-color--7c5fac, #7C5FAC);
  stop-opacity: 0;
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2_qzobga {
  stroke: var(--svg-color--be937f, #BE937F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M16.145 18.292c.19.027.71.033 1.275-.163");
}

.e4nsc89bw {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.339 9.323c.657 0 1.213.453 1.364 1.066a.276.276 0 0 1-.27.343h-2.246a.232.232 0 0 1-.229-.274a1.41 1.41 0 0 1 1.38-1.135");
}

.e9j5vvbvj {
  stop-color: var(--svg-color--72372a, #72372A);
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.eorumbbww {
  d: path("M10.827 4.648c.57-.603 1.648-.604 2.146-.514l.398 1.3c-.254-.04-.297-.002-.488.184c-.139 1.1-1.386 1.768-2.906 2.212c-.15-1.502.11-2.396.85-3.182");
}

.epu6iq_fg {
  stop-color: var(--svg-color--4f3466, #4F3466);
}

.erhusabwh {
  d: path("M15.324 2.834c-1.14-.252-2.165.886-2.283 1.308c1.06 3.569 3.739 3.373 6.384 3.08c1.583-.176 1.755.545 1.89.894c0-3.96-3.367-4.703-5.962-5.276z");
}

.etuvdbcrg {
  d: path("M10.809 9.406h.012l-.01-.267l-.01-.308c.02-.955.578-1.325.816-1.448l.051-.02q.027-.014.052-.021a2.32 2.32 0 0 0 1.197-1.243L13 5.903a.265.265 0 0 1 .465-.051a3.89 3.89 0 0 0 3.21 1.685h3.243c.181 0 1.09.088 1.143 1.341l-.12 3.094c-.123 2.822-2.327 4.717-5.016 4.717s-4.894-1.895-5.018-4.717z");
}

.euze1ubdn {
  d: path("M21.82 17.307c-.642-1.312-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.582 2.995-7.816 3.383-8.741c.42-1.004.809-2.477.215-3.86");
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fa0q4x0wh {
  stop-color: var(--svg-color--8d5e67, #8D5E67);
  stop-opacity: 0;
}

.fqnn-rb2e {
  stop-color: var(--svg-color--7b63b3, #7B63B3);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g82zxu-vf {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.gxgnakb2c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.02 4.091c.024.245.237 1.165.549 1.721");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h17aqmc7c {
  fill: var(--svg-color--7a60bc, #7A60BC);
  d: path("M21.82 17.307c-.642-1.312-1.821-1.75-2.595-1.75h-2.609v2.875h2.47c.168.303.002.85-.102 1.086l-3.94 10.39h3.177c1.067-2.582 2.995-7.816 3.383-8.741c.42-1.004.809-2.477.215-3.86");
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

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.ifq4m0b_p {
  d: path("M13.732 9.596a.9.9 0 0 0-.866 1.136h1.736a1 1 0 0 0 .033-.237a.905.905 0 0 0-.903-.899");
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iky6zuwiy {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M20.791 11.76a1.081 1.081 0 1 0 0-2.164a1.081 1.081 0 0 0 0 2.163");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j4puavbfr {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.354 6.468l-1.435.264a.693.693 0 1 1-.126-1.374h2.357c1.394 0 1.855 1.405 1.912 1.885a3.17 3.17 0 0 0-2.708-.775");
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j9f40ss8t {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m12.51 8.888l-.004.002a.27.27 0 0 1-.278-.463l.002-.001l.003-.002l.01-.005a2 2 0 0 1 .149-.078a3 3 0 0 1 .413-.162c.342-.11.82-.201 1.337-.11a.27.27 0 0 1-.094.531c-.401-.07-.787 0-1.08.093a3 3 0 0 0-.458.195");
}

.jhdqd89ez {
  stop-color: var(--svg-color--342554, #342554);
}

.jletv-brl {
  stop-color: var(--svg-color--8067c6, #8067C6);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.k02lm1bfz {
  fill-rule: evenodd;
  d: path("M23.166 12.097c.214-.438.326-.927.326-1.437a3.3 3.3 0 0 0-.27-1.314h.005a3 3 0 0 0-.283-.517l-.002-.003a3.26 3.26 0 0 1-.53-1.783v-.01A3.32 3.32 0 0 0 19.09 3.71a.54.54 0 0 1-.459-.234a3.33 3.33 0 0 0-2.7-1.386c-1.11 0-2.099.55-2.7 1.386a.57.57 0 0 1-.458.234l-.086.001a3.32 3.32 0 0 0-3.236 3.32v.011c0 .632-.184 1.253-.53 1.783l-.002.004a3.32 3.32 0 0 0-.222 3.267a.52.52 0 0 1 0 .459a3.235 3.235 0 0 0 2.914 4.656h8.64a3.235 3.235 0 0 0 2.915-4.656a.52.52 0 0 1 0-.459m-12.344-2.69h-.013l1.207 2.37c.124 2.823 1.226 0 3.915 0s3.863 3.142 3.987.32l1.144-3.219c-.054-1.253-.963-1.341-1.144-1.341h-3.242a3.89 3.89 0 0 1-3.211-1.685a.266.266 0 0 0-.465.051l-.082.195A2.32 2.32 0 0 1 11.72 7.34l-.052.021l-.051.02c-.238.124-.795.494-.816 1.449l.01.308z");
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k796fybnd {
  stop-color: var(--svg-color--8870c8, #8870C8);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kb-1tmb8e {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.067 8.289c-.325-.08-1.132-.04-1.672.346");
}

.koms7kb5h {
  d: path("m15.546 10.314l-.535 1.712a.543.543 0 0 0 .524.704h.792a.545.545 0 0 0 .524-.704l-.535-1.712c-.115-.38-.65-.38-.77 0");
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.l-n61r67s {
  cx: 8.275px;
  cy: 23.323px;
  r: 6.305px;
}

.l0nudab1i {
  stop-color: var(--svg-color--865144, #865144);
  stop-opacity: 0;
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l71ib0olo {
  fill: var(--svg-color--000, #000);
  d: path("M17.616 10.495c0-.286.228-.515.514-.515a.512.512 0 0 1 .458.752h-.911a.47.47 0 0 1-.061-.237");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj_bse8ns {
  stop-color: var(--svg-color--a3776e, #A3776E);
}

.ljtsggi4h {
  cx: 13.461px;
  cy: 9.98px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.392px;
  ry: 0.199px;
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.m5prodbki {
  fill: var(--svg-color--2f2c32, #2F2C32);
  d: path("M17.081 10.105c.267-.47.674-.842 1.548-.842c.383 0 .752.107 1.08.372c.27.218.235.498.025.603l-.56.32c-.656-.213-1.382-.241-2.093-.453");
}

.ma74w36yx {
  stop-color: var(--svg-color--b68a79, #B68A79);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbuex5b5r {
  stop-color: var(--svg-color--6b47bb, #6B47BB);
}

.md6qzfbic {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.884 8.289c.325-.08 1.132-.04 1.672.346");
}

.miuob-dnm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.064 9.786c.064.086-.07.19-.222.304s-.265.194-.329.108c-.064-.085.008-.247.16-.36c.152-.115.327-.137.391-.052");
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n44b27bdp {
  stop-color: var(--svg-color--7353bf, #7353BF);
}

.n5l_opbqq {
  r: 6.305px;
}

.nh4l3fbho {
  stop-color: var(--svg-color--684c87, #684C87);
  stop-opacity: 0;
}

.ns5jhvbjf {
  d: path("M15.956 15.486h-.04c.1 0 .192 0 .293.01c-.081-.01-.172-.01-.253-.01");
}

.nu--26b9x {
  d: path("M14.553 10.39c0-.291-.236-.485-.3-.543l-.29.28l.178.364z");
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o1tsckbsu {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M11.233 11.76a1.081 1.081 0 1 0 0-2.164a1.081 1.081 0 0 0 0 2.163");
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.on-ymlb8c {
  stop-color: var(--svg-color--b2806f, #B2806F);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.ozroxmy8l {
  stop-color: var(--svg-color--6b47bb, #6B47BB);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prx855tol {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M10.827 4.648c.57-.603 1.648-.604 2.146-.514l.398 1.3c-.254-.04-.297-.002-.488.184c-.139 1.1-1.386 1.768-2.906 2.212c-.15-1.502.11-2.396.85-3.182");
}

.q8d1l4bok {
  stop-color: var(--svg-color--6d4f8c, #6D4F8C);
  stop-opacity: 0;
}

.qbry5nb_d {
  fill: var(--svg-color--795cc2, #795CC2);
  d: path("M9.9 17.307c.641-1.312 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.582-3.292-7.816-3.68-8.741c-.42-1.004-.89-2.477-.297-3.86");
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qgx5q8byi {
  d: path("M11.214 12.298a1.62 1.62 0 1 0 0-3.24a1.62 1.62 0 0 0 0 3.24");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qnar36wle {
  r: 4.086px;
}

.qpg180b3w {
  d: path("M18.13 9.596a.898.898 0 0 1 .866 1.136H17.26a.902.902 0 0 1 .87-1.135");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxmjg8p4i {
  cx: 13.461px;
  cy: 9.98px;
  rx: 0.392px;
  ry: 0.199px;
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r4n8i0bee {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.524 9.323c-.658 0-1.213.453-1.364 1.066a.276.276 0 0 0 .27.343h2.246a.23.23 0 0 0 .228-.274a1.41 1.41 0 0 0-1.38-1.135");
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.roh2cebgd {
  stop-color: var(--svg-color--6349aa, #6349AA);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rw2ievmrq {
  d: path("M5.096 29.893c0-7.96 4.617-9.875 5.375-10.382l5.047 10.382z");
}

.rz_1qnb6a {
  stop-color: var(--svg-color--593d6e, #593D6E);
  stop-opacity: 0;
}

.s2ztaubvo {
  d: path("M26.947 29.893c0-7.96-4.617-9.875-5.375-10.382l-5.047 10.382z");
}

.s4bid24aq {
  d: path("M14.01 15.37h4v1.989c.01.174.045.373.152.53a.8.8 0 0 0 .445.332l.465.165c.076.067.22.478.04.984c-.181.505-2.043 5.51-3.094 8.02v.019l-.005-.01q0 .005-.004.01v-.02c-1.052-2.51-3.186-7.514-3.366-8.02c-.182-.505-.076-.869 0-.937l.68-.191c.218-.062.373-.14.515-.348c.113-.165.158-.389.172-.572z");
}

.sem6ntf8z {
  cx: 10.674px;
  cy: 16.12px;
  r: 4.086px;
}

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.sr-221a-o {
  d: path("M20.791 11.76a1.081 1.081 0 1 0 0-2.164a1.081 1.081 0 0 0 0 2.163");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sv9br1byn {
  stop-color: var(--svg-color--5e40aa, #5E40AA);
  stop-opacity: 0;
}

.szk7albek {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.931 13.61a3.05 3.05 0 0 1-1.431-.348c-.142-.074-.294.09-.205.221a1.945 1.945 0 0 0 3.272 0c.09-.137-.063-.295-.204-.22c-.415.22-.902.346-1.432.346Z");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t3jo2gbov {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.546 10.314l-.535 1.712a.543.543 0 0 0 .524.704h.792a.545.545 0 0 0 .524-.704l-.535-1.712c-.115-.38-.65-.38-.77 0");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tan30xb_g {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m19.688 8.427l-.139.232za.27.27 0 0 1-.278.463l-.005-.002l-.022-.013l-.092-.046a3 3 0 0 0-.344-.136a2.3 2.3 0 0 0-1.08-.093a.27.27 0 0 1-.094-.531c.517-.091.995 0 1.338.11a3.3 3.3 0 0 1 .562.24l.01.005l.003.002z");
}

.tbqxjbcmi {
  stop-color: var(--svg-color--614279, #614279);
  stop-opacity: 0;
}

.tkat5cdin {
  stop-color: var(--svg-color--795cc2, #795CC2);
  stop-opacity: 0;
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tp9z2fb1u {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.324 2.834c-1.14-.252-2.165.886-2.283 1.308c1.06 3.569 3.739 3.373 6.384 3.08c1.583-.176 1.755.545 1.89.894c0-3.96-3.367-4.703-5.962-5.276z");
}

.tqo-vnfob {
  stop-color: var(--svg-color--9078d3, #9078D3);
}

.ttp7yqb-m {
  stop-color: var(--svg-color--9279d5, #9279D5);
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u44j7rbwl {
  stop-color: var(--svg-color--7c60c4, #7C60C4);
  stop-opacity: 0;
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.uoi1brb7t {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.536 10.454l-.688 1.711a.543.543 0 0 0 .524.704h.791a.545.545 0 0 0 .525-.704l-.535-1.711c-.115-.38-.497-.38-.617 0");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.vfgk4hb_x {
  stop-color: var(--svg-color--764c51, #764C51);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
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

.wmoe-d3ab {
  d: path("M18.064 9.786c.064.086-.07.19-.222.304s-.265.194-.329.108c-.064-.085.008-.247.16-.36c.152-.115.327-.137.391-.052");
}

.wnjhqclnr {
  fill: var(--svg-color--27232a, #27232A);
  d: path("M14.782 10.105c-.268-.47-.674-.842-1.548-.842a1.67 1.67 0 0 0-1.08.372c-.271.218-.235.498-.025.603l.56.32c.656-.213 1.381-.241 2.092-.453");
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.wv2o2nbhk {
  stop-color: var(--svg-color--7a67ab, #7A67AB);
}

.x2wiwlbfv {
  d: path("M9.9 17.307c.641-1.312 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.582-3.292-7.816-3.68-8.741c-.42-1.004-.89-2.477-.297-3.86");
}

.x37sucbkr {
  stop-color: var(--svg-color--8870c8, #8870C8);
}

.x4p5bn7mz {
  stop-color: var(--svg-color--2c1c48, #2C1C48);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvf28obeq {
  d: path("M16.29 15.486c.252.01.514.03.777.05c-.263-.02-.515-.04-.778-.05");
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y-a_999zn {
  stop-color: var(--svg-color--7e64c5, #7E64C5);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y41hsabjm {
  stop-color: var(--svg-color--704cc0, #704CC0);
}

.y8qx7dbfv {
  d: path("M20.791 12.298a1.62 1.62 0 1 0 0-3.24a1.62 1.62 0 0 0 0 3.24");
}

.yf2be6b7n {
  d: path("M11.233 11.76a1.081 1.081 0 1 0 0-2.164a1.081 1.081 0 0 0 0 2.163");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.yriwpzb7a {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.931 13.61a3.05 3.05 0 0 1-1.431-.348c-.142-.074-.294.09-.205.221a1.945 1.945 0 0 0 3.272 0c.09-.137-.063-.295-.204-.22c-.415.22-.902.346-1.432.346");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.z0qi4zb3s {
  stop-color: var(--svg-color--684c87, #684C87);
}

.z2_09-bfu {
  d: path("M18.93 10.377a.85.85 0 0 0-.232-.466l-.262.287l.118.23z");
}

.zantcf-1d {
  stop-color: var(--svg-color--775cbc, #775CBC);
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

</style>
