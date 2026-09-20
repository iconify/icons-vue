<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":262};
const content = `<defs><linearGradient id="SVGX0t7eeOW" x1="49.997%" x2="49.997%" y1="100.065%" y2="-.016%"><stop offset="0%" class="wcd69v3sw"/><stop offset="100%" class="u13zszbka"/></linearGradient><linearGradient id="SVGLKBnIsSS" x1="51.682%" x2="51.682%" y1="99.547%" y2="-.213%"><stop offset="0%" class="t3cv40bwm"/><stop offset="100%" class="sx9m_bbse"/></linearGradient><linearGradient id="SVGuPUcAeXy" x1="47.1%" x2="47.1%" y1="99.547%" y2="-.213%"><stop offset="0%" class="t3cv40bwm"/><stop offset="100%" class="sx9m_bbse"/></linearGradient><linearGradient id="SVGSosBNe3f" x1="49.7%" x2="49.7%" y1="99.547%" y2="-.213%"><stop offset="0%" class="t3cv40bwm"/><stop offset="100%" class="sx9m_bbse"/></linearGradient><linearGradient id="SVGwrm1ierl" x1="50.2%" x2="50.2%" y1="99.547%" y2="-.213%"><stop offset="0%" class="t3cv40bwm"/><stop offset="100%" class="sx9m_bbse"/></linearGradient><linearGradient id="SVGitN5Xbov" x1="45.8%" x2="45.8%" y1="99.547%" y2="-.213%"><stop offset="0%" class="t3cv40bwm"/><stop offset="100%" class="sx9m_bbse"/></linearGradient><linearGradient id="SVGIwcdRdnW" x1="46.917%" x2="46.917%" y1="99.547%" y2="-.213%"><stop offset="0%" class="t3cv40bwm"/><stop offset="100%" class="sx9m_bbse"/></linearGradient><linearGradient id="SVGuoU5NeDX" x1="51.2%" x2="51.2%" y1="99.547%" y2="-.213%"><stop offset="0%" class="t3cv40bwm"/><stop offset="100%" class="sx9m_bbse"/></linearGradient><linearGradient id="SVGimbuCcTY" x1="52.6%" x2="52.6%" y1="99.547%" y2="-.213%"><stop offset="0%" class="t3cv40bwm"/><stop offset="100%" class="sx9m_bbse"/></linearGradient><linearGradient id="SVGBC8fCbeW" x1="48.045%" x2="48.045%" y1="99.547%" y2="-.213%"><stop offset="0%" class="t3cv40bwm"/><stop offset="100%" class="sx9m_bbse"/></linearGradient><linearGradient id="SVGYNcfAcWK" x1="49.948%" x2="49.948%" y1="99.943%" y2=".038%"><stop offset="0%" class="zwm-imynq"/><stop offset="100%" class="t9shxr75j"/></linearGradient><linearGradient id="SVGGnqYNdim" x1="66.56%" x2="33.185%" y1="100.135%" y2=".097%"><stop offset="0%" class="e3q0j-xbe"/><stop offset="100%" class="slpric7lb"/></linearGradient><linearGradient id="SVG7CP2weMd" x1="66.768%" x2="33.189%" y1="100.213%" y2=".149%"><stop offset="0%" class="xd8youbhx"/><stop offset="100%" class="zbspyxbqq"/></linearGradient><linearGradient id="SVG0ZERAdZk" x1="66.743%" x2="33.255%" y1="99.893%" y2=".153%"><stop offset="0%" class="phrw0gx1c"/><stop offset="100%" class="ppnk97b3n"/></linearGradient><linearGradient id="SVGdYj8YbYP" x1="66.818%" x2="33.325%" y1="99.886%" y2="-.089%"><stop offset="0%" class="qwl31pb4b"/><stop offset="100%" class="pvjsdpbnl"/></linearGradient><linearGradient id="SVG4VTMvdSF" x1="66.837%" x2="33.388%" y1="99.976%" y2="-.111%"><stop offset="0%" class="vjdklub2a"/><stop offset="100%" class="dmje4jbfa"/></linearGradient><linearGradient id="SVGREJcFemT" x1="1.227%" x2="99.348%" y1="67.606%" y2="31.555%"><stop offset="0%" class="t8o9p1bko"/><stop offset="100%" class="mc8wbebrz"/></linearGradient><linearGradient id="SVG5Id4sbnf" x1="-.197%" x2="97.909%" y1="66.347%" y2="29.438%"><stop offset="0%" class="t8o9p1bko"/><stop offset="100%" class="mc8wbebrz"/></linearGradient><linearGradient id="SVGRwZWgcNf" x1="-4.091%" x2="93.394%" y1="62.746%" y2="25.846%"><stop offset="0%" class="bkq2alc-m"/><stop offset="100%" class="gfj42ybhb"/></linearGradient><linearGradient id="SVG3rWnrd9y" x1="-3.996%" x2="91.182%" y1="62.651%" y2="26.567%"><stop offset="0%" class="bkq2alc-m"/><stop offset="100%" class="gfj42ybhb"/></linearGradient><linearGradient id="SVGGUosgcdd" x1="50.041%" x2="50.041%" y1="100.188%" y2="-.034%"><stop offset="0%" class="zwm-imynq"/><stop offset="100%" class="t9shxr75j"/></linearGradient><linearGradient id="SVGRxBEjdkd" x1="33.328%" x2="66.919%" y1="100.227%" y2=".019%"><stop offset="0%" class="lza2jxbrr"/><stop offset="100%" class="dav3--bzi"/></linearGradient><linearGradient id="SVGezGSLdCr" x1="33.267%" x2="66.85%" y1="100.305%" y2=".228%"><stop offset="0%" class="xuaaxdbdh"/><stop offset="100%" class="uhyae0s0l"/></linearGradient><linearGradient id="SVGf4sDXcoj" x1="33.298%" x2="66.692%" y1="99.811%" y2=".071%"><stop offset="0%" class="s420c8yyv"/><stop offset="100%" class="htczfhbos"/></linearGradient><linearGradient id="SVGy6duabZt" x1="33.174%" x2="66.78%" y1="99.97%" y2="-.173%"><stop offset="0%" class="yr5gnlhoq"/><stop offset="100%" class="w69mz2z0s"/></linearGradient><linearGradient id="SVG2c4UOOug" x1="33.202%" x2="66.569%" y1="99.951%" y2="-.187%"><stop offset="0%" class="xuaaxdbdh"/><stop offset="100%" class="s5-mmfxmg"/></linearGradient><linearGradient id="SVGVJKkzbcK" x1="8.383%" x2="104.985%" y1="26.376%" y2="63.366%"><stop offset="0%" class="kpwshbcqx"/><stop offset="100%" class="pcwwupb6m"/></linearGradient><linearGradient id="SVGm0ZKPeOc" x1="6.806%" x2="103.463%" y1="27.833%" y2="62.708%"><stop offset="0%" class="kpwshbcqx"/><stop offset="100%" class="pcwwupb6m"/></linearGradient><linearGradient id="SVGV9mMtcMp" x1="5.567%" x2="102.209%" y1="29.495%" y2="63.636%"><stop offset="0%" class="kpwshbcqx"/><stop offset="100%" class="pcwwupb6m"/></linearGradient><linearGradient id="SVGm2stqbtY" x1="3.896%" x2="100.537%" y1="29.952%" y2="64.102%"><stop offset="0%" class="flzi6dvyx"/><stop offset="100%" class="jma_ewokh"/></linearGradient><linearGradient id="SVGDLuvTcgf" x1="3.731%" x2="100.403%" y1="31.313%" y2="65.463%"><stop offset="0%" class="u0i2rhzfq"/><stop offset="100%" class="v6-xg6byg"/></linearGradient><linearGradient id="SVGrIAIxcSI" x1="3.582%" x2="100.224%" y1="32.674%" y2="66.815%"><stop offset="0%" class="u0i2rhzfq"/><stop offset="100%" class="v6-xg6byg"/></linearGradient><linearGradient id="SVGCtP5hnIU" x1="2.075%" x2="98.701%" y1="32.975%" y2="67.116%"><stop offset="0%" class="ad23rcohi"/><stop offset="100%" class="va1a6kb9w"/></linearGradient><linearGradient id="SVGI97GL5Kd" x1=".522%" x2="97.179%" y1="34.139%" y2="67.456%"><stop offset="0%" class="r5p6w33po"/><stop offset="100%" class="jn4zb_b0g"/></linearGradient><linearGradient id="SVGzRg8ib6S" x1="2.164%" x2="92.382%" y1="39.322%" y2="60.185%"><stop offset="0%" class="jx3nu12bx"/><stop offset="100%" class="vr1i6z5vu"/></linearGradient><linearGradient id="SVGw0KTodcC" x1="-3.97%" x2="92.687%" y1="37.208%" y2="73.049%"><stop offset="0%" class="jx3nu12bx"/><stop offset="100%" class="vr1i6z5vu"/></linearGradient><linearGradient id="SVG6A6gqL3T" x1="-4.119%" x2="92.522%" y1="36.008%" y2="73.58%"><stop offset="0%" class="jx3nu12bx"/><stop offset="100%" class="vr1i6z5vu"/></linearGradient><linearGradient id="SVG7PcNOder" x1="45.594%" x2="53.241%" y1="48.14%" y2="54.535%"><stop offset=".1%"/><stop offset="100%" class="k05n1gbkm"/></linearGradient><linearGradient id="SVGqp1QhblK" x1="40.335%" x2="60.708%" y1="40.676%" y2="55.055%"><stop offset="0%" class="hwemugkfj"/><stop offset="10%" class="or0r-ybpo"/><stop offset="18.1%" class="c5s3bk4ic"/><stop offset="35.1%" class="hcf_so9lu"/><stop offset="47%" class="ilsaqtb_j"/><stop offset="59.1%" class="i6f-jcbjl"/><stop offset="74.9%" class="e70c6m5-r"/><stop offset="80%" class="fjdyd7b9g"/><stop offset="84.9%" class="pk8v_ye0b"/><stop offset="90%" class="usf9j-bmb"/></linearGradient><linearGradient id="SVGhLeDJbAv" x1="74.136%" x2="18.503%" y1="89.046%" y2="4.378%"><stop offset="27%" class="cvx5isbna"/><stop offset="45%" class="rc0rk9bss"/><stop offset="54%" class="auzejsbba"/><stop offset="73%" class="rc0rk9bss"/></linearGradient><linearGradient id="SVGXYnypdaG" x1="-1.75%" x2="97.917%" y1="55.328%" y2="48.122%"><stop offset="14%" class="usf9j-bmb"/><stop offset="40%" class="r-b8uph3k"/><stop offset="73%" class="i8yjqcc0y"/><stop offset="92%" class="cvx5isbna"/></linearGradient><linearGradient id="SVGqZOCqdLX" x1="52.156%" x2="41.552%" y1="71.394%" y2="26.303%"><stop offset="0%" class="hzwy61bwj"/><stop offset="46%" class="pnk1nc4ac"/><stop offset="70%" class="ecj9p62wy"/><stop offset="91%" class="a6a23-bpx"/></linearGradient><linearGradient id="SVGlWH9dc4r" x1="42.628%" x2="57.838%" y1="42.616%" y2="54.013%"><stop offset="11.5%" class="u2woo1bmb"/><stop offset="37.4%" class="jkg_629vf"/><stop offset="55%" class="reu28fb3r"/><stop offset="75.4%" class="iilmtuttp"/><stop offset="89.2%" class="f3l_5-b3m"/><stop offset="100%" class="vrisxkn0o"/></linearGradient><linearGradient id="SVGMGvB4c7x" x1="29.79%" x2="58.065%" y1="69.5%" y2="23.542%"><stop offset="11.8%" class="azs8ycc_k"/><stop offset="20%" class="me5fx9bta"/><stop offset="34%" class="x5dq9-5cb"/><stop offset="37.4%" class="ax6h9ub6g"/><stop offset="40%" class="zk_d9zbwe"/><stop offset="50%" class="mn6-2ybuq"/><stop offset="56%" class="h-xxuq7ga"/><stop offset="68.8%" class="c2u0t-ppb"/><stop offset="80.7%" class="c0vn3882e"/><stop offset="91.5%" class="j8ec_kb8d"/><stop offset="100%" class="kwqf1mbxy"/></linearGradient><linearGradient id="SVG7oXs5bLB" x1="-.164%" x2="99.957%" y1="50.004%" y2="50.004%"><stop offset="0%" class="zd-f8cc0u"/><stop offset="100%" class="o65s5bc4d"/></linearGradient><linearGradient id="SVGtfMmRbkr" x1="-.19%" x2="99.936%" y1="49.584%" y2="49.584%"><stop offset="0%" class="npxc6ub1d"/><stop offset="41%" class="x0szznb2q"/></linearGradient><linearGradient id="SVGi0Oyqbqt" x1="31.726%" x2="67.025%" y1="89.031%" y2="8.692%"><stop offset="0%" class="nir082ypd"/><stop offset="23%" class="f4gv_-flo"/><stop offset="28.2%" class="xc_bvznwy"/><stop offset="40%" class="hmnctyhqw"/><stop offset="46.4%" class="x-avtub4q"/><stop offset="54.6%" class="j3a28gb1q"/><stop offset="60.7%" class="hrue42b0x"/><stop offset="64%" class="j8xhpdbyc"/></linearGradient><radialGradient id="SVG3edRwb8s" cx="64.482%" cy="29.66%" r="42.357%" fx="64.482%" fy="29.66%" gradientTransform="matrix(-.3233 .89332 -.64265 -.44941 1.044 -.146)"><stop offset="0%"/><stop offset="100%" class="k05n1gbkm"/></radialGradient><radialGradient id="SVGGF6yTcYm" cx="48.301%" cy="48.508%" r="73.404%" fx="48.301%" fy="48.508%" gradientTransform="matrix(.62911 .4402 -.30843 .8979 .329 -.163)"><stop offset="41.7%" class="y94ousb3g"/><stop offset="100%" class="p0qp5poin"/></radialGradient></defs><path fill="url(#SVGX0t7eeOW)" class="pi94j0b2q"/><path class="wz-nrr90i"/><path class="r2zwu0b5o"/><path class="wlp6ojsle"/><path class="tpzcz9inh"/><path class="g7m-aebsl"/><path class="r2ueo6ukp"/><path class="kw3o7ccib"/><path class="bak931b0n"/><path class="dlzwlabvz"/><path class="gs_-mdbuq"/><path fill="url(#SVGLKBnIsSS)" transform="translate(32.768 149.768)" class="oo3kcdb_h"/><path fill="url(#SVGuPUcAeXy)" transform="translate(32.768 149.768)" class="fo0vy72df"/><path fill="url(#SVGSosBNe3f)" transform="translate(32.768 149.768)" class="nivyb-1rr"/><path fill="url(#SVGwrm1ierl)" transform="translate(32.768 149.768)" class="zf8em5btl"/><path fill="url(#SVGitN5Xbov)" transform="translate(32.768 149.768)" class="amlhppbpt"/><path fill="url(#SVGIwcdRdnW)" transform="translate(32.768 149.768)" class="dxz1y0bak"/><path fill="url(#SVGuoU5NeDX)" transform="translate(32.768 149.768)" class="h6xrrq91p"/><path fill="url(#SVGimbuCcTY)" transform="translate(32.768 149.768)" class="jd6cb_r0c"/><path fill="url(#SVGBC8fCbeW)" transform="translate(32.768 149.768)" class="vnh7u6b9a"/><path class="qkoq_nb0u"/><path fill="url(#SVGYNcfAcWK)" transform="translate(90.075 59.802)" class="n6aw-6oqx"/><path fill="url(#SVGGnqYNdim)" transform="translate(90.075 59.802)" class="iokjwev8j"/><path fill="url(#SVG7CP2weMd)" transform="translate(90.075 59.802)" class="obcw86b2u"/><path fill="url(#SVG0ZERAdZk)" transform="translate(90.075 59.802)" class="mq_r0lj3k"/><path fill="url(#SVGdYj8YbYP)" transform="translate(90.075 59.802)" class="xlqn67blp"/><path fill="url(#SVG4VTMvdSF)" transform="translate(90.075 59.802)" class="foevnzbbr"/><path class="wok_s4boi"/><path class="zwx9prbsc"/><path class="m017bab_x"/><path fill="url(#SVGREJcFemT)" transform="translate(90.075 59.802)" class="fc_fu446p"/><path fill="url(#SVG5Id4sbnf)" transform="translate(90.075 59.802)" class="ne0--db_t"/><path class="tmylacijy"/><path fill="url(#SVGRwZWgcNf)" transform="translate(90.075 59.802)" class="dsk5wblvg"/><path fill="url(#SVG3rWnrd9y)" transform="translate(90.075 59.802)" class="g9e8dd76q"/><path class="j4wirvb8n"/><path fill="url(#SVGGUosgcdd)" transform="translate(46.828 60.258)" class="p5hy9tbbb"/><path fill="url(#SVGRxBEjdkd)" transform="translate(46.828 60.258)" class="mavfo6bmo"/><path fill="url(#SVGezGSLdCr)" transform="translate(46.828 60.258)" class="ugw8gabor"/><path fill="url(#SVGf4sDXcoj)" transform="translate(46.828 60.258)" class="ok8x9gbho"/><path fill="url(#SVGy6duabZt)" transform="translate(46.828 60.258)" class="m_b01abqh"/><path fill="url(#SVG2c4UOOug)" transform="translate(46.828 60.258)" class="i4hc95bxu"/><path fill="url(#SVGVJKkzbcK)" transform="translate(46.828 60.258)" class="newnpjuur"/><path fill="url(#SVGm0ZKPeOc)" transform="translate(46.828 60.258)" class="ezkkt5c2s"/><path fill="url(#SVGV9mMtcMp)" transform="translate(46.828 60.258)" class="p9k6_lbyf"/><path fill="url(#SVGm2stqbtY)" transform="translate(46.828 60.258)" class="hbxsvdbbl"/><path fill="url(#SVGDLuvTcgf)" transform="translate(46.828 60.258)" class="w8vv4ib1u"/><path fill="url(#SVGrIAIxcSI)" transform="translate(46.828 60.258)" class="wss9gij-a"/><path fill="url(#SVGCtP5hnIU)" transform="translate(46.828 60.258)" class="oa3x14bzd"/><path fill="url(#SVGI97GL5Kd)" transform="translate(46.828 60.258)" class="lev0l2b1b"/><path class="z1b-k_67r"/><path fill="url(#SVGzRg8ib6S)" transform="translate(46.828 60.258)" class="r73qn6n2r"/><path fill="url(#SVGw0KTodcC)" transform="translate(46.828 60.258)" class="i4h3bcbwi"/><path fill="url(#SVG6A6gqL3T)" transform="translate(46.828 60.258)" class="f0h26yjac"/><path fill="url(#SVG7PcNOder)" transform="translate(68.254)" class="rgivvmnot"/><path fill="url(#SVG3edRwb8s)" transform="translate(68.254)" class="p18w30bkv"/><path fill="url(#SVGGF6yTcYm)" transform="translate(68.254)" class="b8jadc0dz"/><path fill="url(#SVGqp1QhblK)" transform="translate(68.254)" class="fdfw-qg3j"/><path fill="url(#SVGhLeDJbAv)" transform="translate(68.254)" class="joxzc-ean"/><path fill="url(#SVGXYnypdaG)" transform="translate(68.254)" class="k8odsephx"/><path fill="url(#SVGqZOCqdLX)" transform="translate(68.254)" class="ekkozgbuj"/><path fill="url(#SVGlWH9dc4r)" transform="translate(68.254)" class="whbnwnb5m"/><path fill="url(#SVGMGvB4c7x)" transform="translate(68.254)" class="z9yubseoz"/><path fill="url(#SVG7oXs5bLB)" transform="translate(68.254)" class="ex-ltn-sp"/><path fill="url(#SVGtfMmRbkr)" transform="translate(68.254)" class="dgqw5qc9s"/><path fill="url(#SVGi0Oyqbqt)" transform="translate(68.254)" class="lh1o-kbez"/><path class="m1a64sbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:xcode" /></template>
<style>
.a6a23-bpx {
  stop-color: var(--svg-color--7b7d88, #7b7d88);
}

.ad23rcohi {
  stop-color: var(--svg-color--b5ddf8, #b5ddf8);
}

.amlhppbpt {
  d: path("M58.731 2.049h1.139s-1.139 4.324-1.139 8.876c0 4.097 1.139 8.194 1.139 8.194h-1.14s-1.138-4.097-1.138-8.194c0-4.552 1.138-8.876 1.138-8.876");
}

.auzejsbba {
  stop-color: var(--svg-color--b0b0bc, #b0b0bc);
}

.ax6h9ub6g {
  stop-color: var(--svg-color--1d1f22, #1d1f22);
}

.azs8ycc_k {
  stop-color: var(--svg-color--6d7078, #6d7078);
  stop-opacity: 0;
}

.b8jadc0dz {
  d: path("M1.623 238.309c-.683 1.366-1.821 2.959-1.593 5.463c.227 9.332 15.477 17.98 24.354 17.98c6.146 0 8.194-2.503 10.47-7.055s-30.727-21.85-33.231-16.388");
}

.bak931b0n {
  fill: var(--svg-color--65b1ee, #65b1ee);
  d: path("M34.597 160.921h159.1v-.91h-159.1z");
}

.bkq2alc-m {
  stop-color: var(--svg-color--00b4ef, #00b4ef);
}

.c0vn3882e {
  stop-color: var(--svg-color--63666b, #63666b);
}

.c2u0t-ppb {
  stop-color: var(--svg-color--4b4d51, #4b4d51);
}

.c5s3bk4ic {
  stop-color: var(--svg-color--8b8c95, #8b8c95);
}

.cvx5isbna {
  stop-color: var(--svg-color--262b33, #262b33);
}

.dav3--bzi {
  stop-color: var(--svg-color--71cff4, #71cff4);
}

.dgqw5qc9s {
  d: path("M57.615 12.746c2.96-1.138 7.056-1.82 14.795-1.365c9.56.455 21.623 4.097 26.63 8.649c2.504 2.276 2.277.455-.455-2.504C91.53 9.332 80.832 7.511 66.947 7.284c-1.593-.228-6.828 2.73-9.332 5.462");
}

.dlzwlabvz {
  fill: var(--svg-color--8ec6f3, #8ec6f3);
  d: path("M36.19 155.231h156.141l.228.455l.227.455H35.735l.227-.455z");
}

.dmje4jbfa {
  stop-color: var(--svg-color--bce7fa, #bce7fa);
}

.dsk5wblvg {
  d: path("m25.552 19.862l.455.91s-4.324-1.138-9.332 1.593c-4.325 2.732-5.235 7.056-5.235 7.056l-.455-.91s.455-3.87 5.235-6.828c5.007-3.187 9.332-1.821 9.332-1.821");
}

.dxz1y0bak {
  d: path("M47.579 2.049h1.138s-1.594 4.324-1.594 8.876c0 4.097 1.594 8.194 1.594 8.194h-1.138s-1.594-4.097-1.594-8.194c0-4.552 1.594-8.876 1.594-8.876");
}

.e3q0j-xbe {
  stop-color: var(--svg-color--2b90e7, #2b90e7);
}

.e70c6m5-r {
  stop-color: var(--svg-color--87898f, #87898f);
}

.ecj9p62wy {
  stop-color: var(--svg-color--474951, #474951);
}

.ekkozgbuj {
  d: path("M125.216 59.862c1.138-1.821 6.373-9.788 8.877-12.291c2.503-2.504 8.876-9.105 14.34-10.015c5.462-.91 11.152 10.242 9.331 12.518c-1.365 1.594-3.642-.227-6.373-2.503c-2.731-2.049-4.552-6.146-13.201.455c-2.96 2.276-5.918 4.097-12.747 13.884c-1.82 2.504-1.365-.227-.227-2.048");
}

.ex-ltn-sp {
  d: path("M106.324 45.295c-1.82-16.844-5.918-32.776-48.709-32.549c2.732-2.731 9.332-5.462 9.332-5.462L57.615 6.6s1.366-1.138 4.097-1.366c25.037-2.048 47.343 3.187 45.75 35.735c-.228 5.235-.683 7.511-1.138 4.325");
}

.ezkkt5c2s {
  d: path("m66.522 19.406l-.455.91s4.552-1.365 9.332 1.367c4.552 2.503 5.462 6.828 5.462 6.828l.456-.91s-.456-4.098-5.463-6.829c-5.235-2.959-9.332-1.366-9.332-1.366");
}

.f0h26yjac {
  d: path("m4.612 126.611l.455-.91s.455 4.78 5.918 7.739c5.007 2.731 8.877.682 8.877.682l-.683.91s-3.414 2.505-8.877-.682c-5.69-3.186-5.69-7.739-5.69-7.739");
}

.f3l_5-b3m {
  stop-color: var(--svg-color--323945, #323945);
}

.f4gv_-flo {
  stop-color: var(--svg-color--244668, #244668);
}

.fc_fu446p {
  d: path("m47.63 58.1l.455.91s-3.869 1.822-7.738 3.87c-3.642 2.049-6.829 4.78-6.829 4.78l-.455-.91s3.414-2.732 6.828-4.78c3.87-2.049 7.74-3.87 7.74-3.87");
}

.fdfw-qg3j {
  d: path("M106.552 44.612s23.444 5.69 25.264 7.283c1.821 1.594-2.958 10.698-3.869 12.064c-7.511 9.104-30.955 59.406-30.955 59.406l-21.623-12.29s19.347-35.963 26.175-48.71c4.325-8.649 5.008-17.753 5.008-17.753");
}

.fjdyd7b9g {
  stop-color: var(--svg-color--8e8f94, #8e8f94);
}

.flzi6dvyx {
  stop-color: var(--svg-color--b0dff8, #b0dff8);
}

.fo0vy72df {
  d: path("M137.485 2.049h-1.138s3.414 3.186 3.414 8.876c0 5.008-3.414 8.194-3.414 8.194h1.138s3.414-2.503 3.414-8.194c-.227-6.145-3.414-8.876-3.414-8.876");
}

.foevnzbbr {
  d: path("m15.537 3.474l74.657 129.283v1.365L14.171 2.791l.456.227l.455.228z");
}

.g7m-aebsl {
  fill: var(--svg-color--0a93e9, #0a93e9);
  d: path("M42.791 151.817h142.484c4.553 0 8.422 3.641 8.422 8.421v.228c0 4.552-3.642 8.421-8.422 8.421H42.791c-4.553 0-8.422-3.641-8.422-8.421v-.455c.228-4.553 3.87-8.194 8.422-8.194");
}

.g9e8dd76q {
  d: path("m20.09 10.074l.682.91s-4.552-1.82-9.787 1.139c-5.008 3.186-5.008 7.511-5.008 7.511l-.682-.91s-.456-3.87 5.007-7.284c5.69-3.414 9.787-1.366 9.787-1.366");
}

.gfj42ybhb {
  stop-color: var(--svg-color--c3e9fa, #c3e9fa);
}

.gs_-mdbuq {
  fill: var(--svg-color--95caf3, #95caf3);
  d: path("M39.604 152.499h149.313l.683.228l.683.455H38.238l.683-.455z");
}

.h-xxuq7ga {
  stop-color: var(--svg-color--292a2e, #292a2e);
}

.h6xrrq91p {
  d: path("M36.426 2.049h1.138s-2.276 3.641-2.276 8.876c0 4.553 2.276 8.194 2.276 8.194h-1.138s-2.277-3.641-2.277-8.194c0-5.235 2.277-8.876 2.277-8.876");
}

.hbxsvdbbl {
  d: path("m55.369 38.753l-.455.91s4.552.684 8.421 2.96c3.642 2.048 6.373 5.462 6.373 5.462l.456-.91s-2.732-3.414-6.373-5.463c-3.87-2.276-8.422-2.959-8.422-2.959");
}

.hcf_so9lu {
  stop-color: var(--svg-color--787a83, #787a83);
}

.hmnctyhqw {
  stop-color: var(--svg-color--040506, #040506);
}

.hrue42b0x {
  stop-color: var(--svg-color--868691, #868691);
}

.htczfhbos {
  stop-color: var(--svg-color--bee8fa, #bee8fa);
}

.hwemugkfj {
  stop-color: var(--svg-color--344351, #344351);
}

.hzwy61bwj {
  stop-color: var(--svg-color--101215, #101215);
  stop-opacity: 0.1;
}

.i4h3bcbwi {
  d: path("m10.302 116.824l.455-.91s1.138 4.552 6.146 7.283c4.552 2.504 8.649 1.138 8.649 1.138l-.455.91s-3.642 1.594-8.65-1.137c-5.235-2.96-6.145-7.284-6.145-7.284");
}

.i4hc95bxu {
  d: path("M27.6 89.51L77.675 2.79l-.455.228l-.456.228l-.227.228S48.768 51.5 26.917 89.51zm-12.063 20.94A5171 5171 0 0 1 1.88 134.123v-1.82s5.008-8.65 12.747-22.079c.455.228.455.228.91.228");
}

.i6f-jcbjl {
  stop-color: var(--svg-color--777982, #777982);
}

.i8yjqcc0y {
  stop-color: var(--svg-color--475768, #475768);
}

.iilmtuttp {
  stop-color: var(--svg-color--4e5057, #4e5057);
}

.ilsaqtb_j {
  stop-color: var(--svg-color--71747d, #71747d);
}

.iokjwev8j {
  d: path("m1.88 11.212l74.657 129.511l.455.228l.455.227l.455.228L1.88 9.847z");
}

.j3a28gb1q {
  stop-color: var(--svg-color--65656e, #65656e);
}

.j4wirvb8n {
  fill: var(--svg-color--fff, #fff);
  d: path("M94.913 149.768c19.803-34.14 42.565-73.744 42.565-73.744c2.959-5.008 1.138-11.38-3.87-14.34s-11.38-1.139-14.34 3.869c0 0-27.768 48.253-48.708 84.216zm-12.29 20.94c-9.56 16.389-16.161 28.225-16.161 28.225c-2.959 5.007-9.332 6.828-14.34 3.87c-5.007-2.96-6.828-9.333-3.869-14.34c0 0 3.87-7.056 10.015-17.526c7.739-.228 21.85-.228 24.354-.228");
}

.j8ec_kb8d {
  stop-color: var(--svg-color--72757b, #72757b);
}

.j8xhpdbyc {
  stop-color: var(--svg-color--92929e, #92929e);
}

.jd6cb_r0c {
  d: path("M25.273 2.049h1.138s-3.414 3.186-3.414 8.876c0 5.008 3.414 8.194 3.414 8.194h-1.138s-3.415-2.503-3.415-8.194c.228-6.145 3.415-8.876 3.415-8.876");
}

.jkg_629vf {
  stop-color: var(--svg-color--3d414e, #3d414e);
}

.jma_ewokh {
  stop-color: var(--svg-color--52bdf2, #52bdf2);
}

.jn4zb_b0g {
  stop-color: var(--svg-color--46aaee, #46aaee);
}

.joxzc-ean {
  d: path("M160.723 32.776c4.097 2.959 9.56 2.276 13.884 1.593c2.96-.455-1.593 3.87-6.6 13.885c-5.008 10.014-4.78 10.697-5.463 10.014s-23.216-13.429-22.533-14.567c.91-1.138 4.552-25.947 6.373-25.264c6.6 1.593 7.738 9.56 14.34 14.339");
}

.jx3nu12bx {
  stop-color: var(--svg-color--8fc1f2, #8fc1f2);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k8odsephx {
  d: path("M125.671 60.772c1.593-2.504 8.877-17.981 20.485-17.981c5.235 0 15.25 13.201 16.16 15.022c.683 1.594-1.593 7.967-2.73 5.008c-1.367-3.414-7.057-10.698-13.202-10.698c-6.146 0-14.568 7.056-16.616 9.56c-2.049 2.276-5.69 1.593-4.097-.91");
}

.kpwshbcqx {
  stop-color: var(--svg-color--c1e7fa, #c1e7fa);
}

.kw3o7ccib {
  fill: var(--svg-color--319dec, #319dec);
  d: path("M35.962 165.246h156.142l.455-.683H35.507z");
}

.kwqf1mbxy {
  stop-color: var(--svg-color--777a80, #777a80);
}

.lev0l2b1b {
  d: path("m32.608 78.358l.455-.91s3.642 2.73 7.511 4.78a93 93 0 0 0 7.284 3.64l-.455.684s-3.87-1.594-7.512-3.642c-3.869-2.049-7.283-4.552-7.283-4.552");
}

.lh1o-kbez {
  d: path("m175.063 34.37l12.518 6.372s-4.78 6.374-8.649 13.657c-4.097 7.739-6.828 16.16-6.828 16.16l-12.064-7.283s2.96-8.194 7.284-16.16c3.414-6.601 7.739-12.747 7.739-12.747");
}

.lza2jxbrr {
  stop-color: var(--svg-color--3194e9, #3194e9);
}

.m_b01abqh {
  d: path("M31.015 89.51c22.533-38.92 50.53-87.63 50.53-87.63h-.911s-27.996 48.482-50.53 87.63zm-13.202 20.94c-9.104 15.706-15.25 26.404-15.25 26.404l.228.455l.227.455s6.601-11.38 15.933-27.313z");
}

.m017bab_x {
  fill: var(--svg-color--4da7ee, #4da7ee);
  d: path("m160.239 156.596l-.456-.91s-2.958 3.87-6.828 5.918c-3.642 2.048-7.966 2.731-7.966 2.731l.455.91s4.325-.682 7.966-2.73c3.642-2.05 6.829-5.919 6.829-5.919");
}

.m1a64sbfa {
  fill: var(--svg-color--bfc0d0, #bfc0d0);
  d: path("M255.835 40.742c.91.456-2.048 7.512-6.373 15.706c-4.324 8.194-8.421 14.567-9.104 14.111c-.91-.455 2.048-7.51 6.373-15.705c4.097-8.194 8.194-14.567 9.104-14.112");
}

.mavfo6bmo {
  d: path("m44.899 89.51l45.295-78.298V9.847S65.156 53.32 44.216 89.51zm-12.291 20.94l-17.299 30.046l-.682.455l-.683.227s7.739-13.429 17.753-30.727z");
}

.mc8wbebrz {
  stop-color: var(--svg-color--b9dff6, #b9dff6);
}

.me5fx9bta {
  stop-color: var(--svg-color--6d7078, #6d7078);
  stop-opacity: 0.7;
}

.mn6-2ybuq {
  stop-color: var(--svg-color--16171a, #16171a);
}

.mq_r0lj3k {
  d: path("m5.75 3.474l79.664 137.704l.683-.455L6.433 3.018z");
}

.n6aw-6oqx {
  d: path("M17.813 6.205L89.055 129.57c2.277 3.87.91 9.105-2.958 11.38l-.456.228c-3.87 2.277-9.104.91-11.38-2.959L3.018 14.627c-2.276-3.87-.91-9.105 2.96-11.381l.227-.228c4.097-2.276 9.332-.91 11.608 3.187");
}

.ne0--db_t {
  d: path("m42.168 48.54l.455.911s-4.325 1.366-7.967 3.642c-3.641 2.048-6.6 5.235-6.6 5.235l-.456-.91s2.96-3.187 6.601-5.236c3.642-2.503 7.967-3.641 7.967-3.641");
}

.newnpjuur {
  d: path("m71.985 9.62l-.456.91s4.097-2.049 9.56.91c5.008 2.731 5.235 7.511 5.235 7.511l.455-.91s.456-4.325-5.235-7.511c-5.69-3.187-9.56-.91-9.56-.91");
}

.nir082ypd {
  stop-color: var(--svg-color--858997, #858997);
}

.nivyb-1rr {
  d: path("M80.81 2.049h1.138v17.07H80.81z");
}

.npxc6ub1d {
  stop-color: var(--svg-color--767880, #767880);
}

.o65s5bc4d {
  stop-color: var(--svg-color--29292d, #29292d);
}

.oa3x14bzd {
  d: path("m38.071 68.57l.455-.91l14.794 8.422l-.455.91z");
}

.obcw86b2u {
  d: path("m2.563 6.888l78.071 135.201h.91L3.018 6.205l-.227.455z");
}

.ok8x9gbho {
  d: path("M36.477 89.51c22.534-38.92 49.62-86.036 49.62-86.036l-.683-.456l-50.075 86.493zm-12.29 21.169c-10.016 17.526-17.527 30.5-17.527 30.5l-.683-.456s7.284-12.746 17.299-30.044c.455-.228.227-.228.91 0");
}

.oo3kcdb_h {
  d: path("M148.41 2.049h-1.138s3.87 2.73 3.87 8.876c0 5.69-3.87 8.194-3.87 8.194h1.138s3.87-1.82 3.87-8.194c0-6.828-3.87-8.876-3.87-8.876");
}

.or0r-ybpo {
  stop-color: var(--svg-color--9697a0, #9697a0);
}

.p0qp5poin {
  stop-color: var(--svg-color--3d4651, #3d4651);
}

.p18w30bkv {
  d: path("m114.518 18.892l45.522 21.623v65.324C144.335 98.328 39.18 48.254 39.18 48.254s7.283-15.25 14.112-29.362z");
}

.p5hy9tbbb {
  d: path("M45.582 89.51c20.03-34.596 43.246-74.883 43.246-74.883c2.276-3.87.91-9.105-2.96-11.381l-.227-.228c-3.87-2.276-9.104-.91-11.38 2.96c0 0-27.314 47.342-48.254 83.533zm-12.064 20.94c-9.104 15.934-15.705 27.314-15.705 27.314c-2.276 3.87-7.283 5.235-11.38 2.96h-.456c-3.869-2.277-5.235-7.284-2.959-11.381c0 0 4.325-7.512 10.926-18.892z");
}

.p9k6_lbyf {
  d: path("m60.832 28.966l-.456.91s4.097-.227 8.65 2.504c4.097 2.276 6.145 5.918 6.145 5.918l.455-.91s-2.048-3.642-6.145-5.918c-4.325-2.504-8.65-2.504-8.65-2.504");
}

.pcwwupb6m {
  stop-color: var(--svg-color--89d4f5, #89d4f5);
}

.phrw0gx1c {
  stop-color: var(--svg-color--3696ea, #3696ea);
}

.pi94j0b2q {
  d: path("M49.847 18.892h128.6c27.541 0 49.847 22.306 49.847 49.847v128.6c0 27.54-22.306 49.847-49.847 49.847h-128.6C22.306 247.186 0 224.88 0 197.339v-128.6c0-27.541 22.306-49.847 49.847-49.847");
}

.pk8v_ye0b {
  stop-color: var(--svg-color--3d3b42, #3d3b42);
}

.pnk1nc4ac {
  stop-color: var(--svg-color--101215, #101215);
  stop-opacity: 0.7;
}

.ppnk97b3n {
  stop-color: var(--svg-color--90d9f6, #90d9f6);
}

.pvjsdpbnl {
  stop-color: var(--svg-color--b5e5f9, #b5e5f9);
}

.qkoq_nb0u {
  fill: var(--svg-color--fff, #fff);
  d: path("m109.709 65.097l71.015 122.91c2.959 5.007 1.138 11.38-3.87 14.34c-5.007 2.958-11.38 1.137-14.34-3.87L91.501 75.567c-2.959-5.008-1.138-11.38 3.87-14.34c5.007-2.959 11.38-1.138 14.339 3.87");
}

.qwl31pb4b {
  stop-color: var(--svg-color--3097ea, #3097ea);
}

.r-b8uph3k {
  stop-color: var(--svg-color--9899a5, #9899a5);
}

.r2ueo6ukp {
  fill: var(--svg-color--1694ea, #1694ea);
  d: path("M39.377 167.977h149.54l1.138-.683H38.238z");
}

.r2zwu0b5o {
  fill: var(--svg-color--69c5f3, #69c5f3);
  d: path("M114.488 39.377c-51.44 0-93.32 41.88-93.32 93.32s41.88 93.32 93.32 93.32c51.668 0 93.321-41.88 93.321-93.32s-41.88-93.32-93.32-93.32m0 185.275c-50.757 0-91.954-41.197-91.954-91.955s41.197-91.955 91.954-91.955c50.758 0 91.955 41.198 91.955 91.955c0 50.758-41.197 91.955-91.955 91.955");
}

.r5p6w33po {
  stop-color: var(--svg-color--96cef4, #96cef4);
}

.r73qn6n2r {
  d: path("M20.09 110.45c.91.684 1.82 1.367 2.958 2.05c4.097 2.276 8.194 2.048 8.194 2.048l-.455.91s-4.097.228-8.194-2.048a19 19 0 0 1-3.87-2.96z");
}

.rc0rk9bss {
  stop-color: var(--svg-color--74747e, #74747e);
}

.reu28fb3r {
  stop-color: var(--svg-color--474a54, #474a54);
}

.rgivvmnot {
  d: path("M56.932 247.413L154.35 42.791l-24.582-11.608L28.253 243.999s3.187 1.594 7.284 3.414z");
}

.s420c8yyv {
  stop-color: var(--svg-color--66abee, #66abee);
}

.s5-mmfxmg {
  stop-color: var(--svg-color--afe3f9, #afe3f9);
}

.slpric7lb {
  stop-color: var(--svg-color--00b6ef, #00b6ef);
}

.sx9m_bbse {
  stop-color: var(--svg-color--dbedfb, #dbedfb);
}

.t3cv40bwm {
  stop-color: var(--svg-color--1492e7, #1492e7);
}

.t8o9p1bko {
  stop-color: var(--svg-color--00a4ec, #00a4ec);
}

.t9shxr75j {
  stop-color: var(--svg-color--00b5ef, #00b5ef);
}

.tmylacijy {
  fill: var(--svg-color--9dd4f7, #9dd4f7);
  d: path("M122 100.832c2.959-.911 5.235-1.366 5.235-1.366l-.455-.91s-2.049.227-4.325 1.137c-1.365.456-1.593 1.594-.455 1.138");
}

.tpzcz9inh {
  fill: var(--svg-color--fff, #fff);
  d: path("M43.246 149.768h142.03c5.917 0 10.47 4.78 10.47 10.47c0 5.918-4.78 10.47-10.47 10.47H43.245c-5.917 0-10.469-4.78-10.469-10.47c-.228-5.69 4.552-10.47 10.47-10.47");
}

.u0i2rhzfq {
  stop-color: var(--svg-color--b4def8, #b4def8);
}

.u13zszbka {
  stop-color: var(--svg-color--00c3f2, #00c3f2);
}

.u2woo1bmb {
  stop-color: var(--svg-color--2c3952, #2c3952);
}

.ugw8gabor {
  d: path("M41.485 89.51L89.283 6.889l-.228-.455l-.227-.456S62.653 51.272 40.802 89.283zM29.42 110.45l-18.209 31.411h-.91s7.739-13.429 18.209-31.638c.455.228.91.228.91.228");
}

.uhyae0s0l {
  stop-color: var(--svg-color--a2def8, #a2def8);
}

.usf9j-bmb {
  stop-color: var(--svg-color--606e84, #606e84);
}

.v6-xg6byg {
  stop-color: var(--svg-color--4eb5f0, #4eb5f0);
}

.va1a6kb9w {
  stop-color: var(--svg-color--46aeee, #46aeee);
}

.vjdklub2a {
  stop-color: var(--svg-color--3a98ea, #3a98ea);
}

.vnh7u6b9a {
  d: path("M14.347 2.049h1.138s-3.869 2.73-3.869 8.876c0 5.69 3.87 8.194 3.87 8.194h-1.139s-3.87-1.82-3.87-8.194c0-6.828 3.87-8.876 3.87-8.876");
}

.vr1i6z5vu {
  stop-color: var(--svg-color--3193ea, #3193ea);
}

.vrisxkn0o {
  stop-color: var(--svg-color--143052, #143052);
}

.w69mz2z0s {
  stop-color: var(--svg-color--b1e3f9, #b1e3f9);
}

.w8vv4ib1u {
  d: path("m49.679 48.313l-.456.91s4.325 1.139 8.194 3.415c3.642 2.048 6.601 5.007 6.601 5.007l.455-.91s-2.959-2.96-6.6-5.008c-3.642-2.048-8.194-3.414-8.194-3.414");
}

.wcd69v3sw {
  stop-color: var(--svg-color--1578e4, #1578e4);
}

.whbnwnb5m {
  d: path("M96.992 126.324c.91-1.82 2.048-4.552-.455-6.6c-2.732-2.049-15.478-8.877-17.754-9.333s-4.097 0-5.007 1.594c-.91 1.593-70.787 121.316-72.153 124.73s-1.593 5.919.455 6.601s25.493 11.836 27.769 14.34s3.414-.228 4.324-1.593c4.325-5.463 61.683-127.918 62.821-129.739");
}

.wlp6ojsle {
  fill: var(--svg-color--68c5f4, #68c5f4);
  d: path("M114.488 58.496c-41.197 0-74.428 33.231-74.428 74.429s33.23 74.201 74.428 74.201s74.43-33.231 74.43-74.429s-33.46-74.2-74.43-74.2m0 147.037c-40.287 0-72.835-32.548-72.835-72.836S74.2 59.862 114.488 59.862s72.836 32.548 72.836 72.835c0 40.288-32.776 72.836-72.836 72.836");
}

.wok_s4boi {
  fill: var(--svg-color--3c98ea, #3c98ea);
  d: path("m176.855 185.275l-.456-.91s-.455 4.552-5.463 7.739c-4.78 2.959-9.104.91-9.104.91l.455.91s3.642 2.504 9.105-.91c5.462-3.187 5.462-7.739 5.462-7.739m-5.69-9.56l-.456-.91s-1.138 4.552-5.918 7.284c-4.325 2.731-8.65 1.365-8.65 1.365l.456.91s3.87 1.594 8.877-1.365s5.69-7.283 5.69-7.283");
}

.wss9gij-a {
  d: path("m44.216 57.873l-.683.91s4.097 1.593 7.967 3.87c3.641 2.048 6.828 4.552 6.828 4.552l.455-.91s-3.186-2.504-6.828-4.553s-7.739-3.87-7.739-3.87");
}

.wz-nrr90i {
  fill: var(--svg-color--fff, #fff);
  d: path("M174.578 31.183H53.716c-22.988 0-41.653 18.664-41.653 41.653v120.861c0 22.989 18.665 41.653 41.653 41.653h120.862c22.989 0 41.653-18.664 41.653-41.653V72.608c0-22.989-18.664-41.425-41.653-41.425m38.238 162.97a37.69 37.69 0 0 1-37.783 37.783H53.261c-20.713 0-37.783-16.843-37.783-37.784v-122A37.69 37.69 0 0 1 53.26 34.37h122c20.712 0 37.783 16.844 37.783 37.784v122z");
}

.x-avtub4q {
  stop-color: var(--svg-color--313236, #313236);
}

.x0szznb2q {
  stop-color: var(--svg-color--0c0a0b, #0c0a0b);
}

.x5dq9-5cb {
  stop-color: var(--svg-color--35363a, #35363a);
}

.xc_bvznwy {
  stop-color: var(--svg-color--1a3249, #1a3249);
}

.xd8youbhx {
  stop-color: var(--svg-color--3795ea, #3795ea);
}

.xlqn67blp {
  d: path("m11.44 2.108l77.843 134.973l-.228.456l-.227.455L10.302 1.88h.455z");
}

.xuaaxdbdh {
  stop-color: var(--svg-color--5aa6ec, #5aa6ec);
}

.y94ousb3g {
  stop-color: var(--svg-color--0c0c12, #0c0c12);
}

.yr5gnlhoq {
  stop-color: var(--svg-color--7bb6f0, #7bb6f0);
}

.z1b-k_67r {
  fill: var(--svg-color--73b9f1, #73b9f1);
  d: path("M75.794 149.768c-1.138-.91-1.82-1.593-1.82-1.593l.454-.91s1.366 1.138 3.187 2.504z");
}

.z9yubseoz {
  d: path("M126.809 59.407c1.138-1.594 3.87-6.146 7.284-10.243c2.276-2.731 14.567-8.65 17.298-18.209c1.593-5.235-.91-10.47-4.325-12.746C135.458 11.153 115.428 0 86.066 0C66.265 0 57.844 6.6 57.844 6.6h10.015l34.824 13.657l4.325 18.21s.455 6.145-1.593 13.2c-1.366 5.691-1.821 9.105-3.87 14.795c1.593.683 5.235-1.82 9.332-.682c3.642.91 5.918 5.918 8.422 2.959c4.324-5.69 5.69-6.829 7.511-9.332");
}

.zbspyxbqq {
  stop-color: var(--svg-color--49c4f2, #49c4f2);
}

.zd-f8cc0u {
  stop-color: var(--svg-color--4a4d56, #4a4d56);
}

.zf8em5btl {
  d: path("M69.657 2.049h1.138s-.455 4.324-.455 8.876c0 4.097.455 8.194.455 8.194h-1.138s-.455-4.097-.455-8.194c0-4.552.455-8.876.455-8.876");
}

.zk_d9zbwe {
  stop-color: var(--svg-color--101215, #101215);
}

.zwm-imynq {
  stop-color: var(--svg-color--1285e7, #1285e7);
}

.zwx9prbsc {
  fill: var(--svg-color--4ca4ed, #4ca4ed);
  d: path("m165.701 166.156l-.455-.91s-2.048 3.869-6.373 6.373c-3.87 2.276-8.194 2.276-8.194 2.276l.455.91s4.097 0 8.194-2.276c4.325-2.504 6.373-6.373 6.373-6.373");
}

</style>
