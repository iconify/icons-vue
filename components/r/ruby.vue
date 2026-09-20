<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":255};
const content = `<defs><linearGradient id="SVGp7IY8bkc" x1="84.75%" x2="58.254%" y1="111.399%" y2="64.584%"><stop offset="0%" class="j1y0librw"/><stop offset="0%" class="j1y0librw"/><stop offset="41%" class="jl8pcyvuf"/><stop offset="99%" class="anp5c3pdg"/><stop offset="100%" class="anp5c3pdg"/></linearGradient><linearGradient id="SVGUgNYzcuh" x1="116.651%" x2="1.746%" y1="60.89%" y2="19.288%"><stop offset="0%" class="h8fnprbnu"/><stop offset="0%" class="h8fnprbnu"/><stop offset="99%" class="q7xz9abfp"/><stop offset="100%" class="q7xz9abfp"/></linearGradient><linearGradient id="SVG511Aleka" x1="75.774%" x2="38.978%" y1="219.327%" y2="7.829%"><stop offset="0%" class="h8fnprbnu"/><stop offset="0%" class="h8fnprbnu"/><stop offset="99%" class="q7xz9abfp"/><stop offset="100%" class="q7xz9abfp"/></linearGradient><linearGradient id="SVGuISx0ckJ" x1="50.012%" x2="66.483%" y1="7.234%" y2="79.135%"><stop offset="0%" class="vc--wpv5i"/><stop offset="0%" class="vc--wpv5i"/><stop offset="23%" class="wr97chdyu"/><stop offset="46%" class="oyjo3ex1c"/><stop offset="99%" class="wxf-xc86f"/><stop offset="100%" class="wxf-xc86f"/></linearGradient><linearGradient id="SVGp2ih7dhN" x1="46.174%" x2="49.932%" y1="16.348%" y2="83.047%"><stop offset="0%" class="vc--wpv5i"/><stop offset="0%" class="vc--wpv5i"/><stop offset="23%" class="q9tep7byl"/><stop offset="56%" class="vgglilblh"/><stop offset="99%" class="ezidwnbja"/><stop offset="100%" class="ezidwnbja"/></linearGradient><linearGradient id="SVGVVXNPbRt" x1="36.965%" x2="49.528%" y1="15.594%" y2="92.478%"><stop offset="0%" class="vc--wpv5i"/><stop offset="0%" class="vc--wpv5i"/><stop offset="18%" class="dpr9tb3ch"/><stop offset="40%" class="lsv7azf7j"/><stop offset="99%" class="ezidwnbja"/><stop offset="100%" class="ezidwnbja"/></linearGradient><linearGradient id="SVGpaPWneGk" x1="13.609%" x2="85.764%" y1="58.346%" y2="-46.717%"><stop offset="0%" class="vc--wpv5i"/><stop offset="0%" class="vc--wpv5i"/><stop offset="54%" class="w_afh7bgq"/><stop offset="99%" class="i_f-8ebbv"/><stop offset="100%" class="i_f-8ebbv"/></linearGradient><linearGradient id="SVG1WvP2bcC" x1="27.624%" x2="50.745%" y1="21.135%" y2="79.056%"><stop offset="0%" class="vc--wpv5i"/><stop offset="0%" class="vc--wpv5i"/><stop offset="31%" class="w8ttm0bgd"/><stop offset="99%" class="qw5y8xbnh"/><stop offset="100%" class="qw5y8xbnh"/></linearGradient><linearGradient id="SVGtihA7dCK" x1="-20.667%" x2="104.242%" y1="122.282%" y2="-6.342%"><stop offset="0%" class="s8aw0sl5f"/><stop offset="0%" class="s8aw0sl5f"/><stop offset="7%" class="vc--wpv5i"/><stop offset="17%" class="vc--wpv5i"/><stop offset="27%" class="ug4qrab9a"/><stop offset="33%" class="gk6kz_ald"/><stop offset="46%" class="yjb2dqbqe"/><stop offset="72%" class="ddk317bha"/><stop offset="99%" class="f4ld04byb"/><stop offset="100%" class="f4ld04byb"/></linearGradient><linearGradient id="SVG4PNQfcAN" x1="58.792%" x2="11.964%" y1="65.205%" y2="50.128%"><stop offset="0%" class="six_5zb0y"/><stop offset="0%" class="six_5zb0y"/><stop offset="54%" class="cqcs1lp7p"/><stop offset="99%" class="u0l4xx4ah"/><stop offset="100%" class="u0l4xx4ah"/></linearGradient><linearGradient id="SVG7JSnDYmr" x1="79.319%" x2="23.088%" y1="62.754%" y2="17.888%"><stop offset="0%" class="oe74w3r0p"/><stop offset="0%" class="oe74w3r0p"/><stop offset="99%" class="veuf6qxqw"/><stop offset="100%" class="veuf6qxqw"/></linearGradient><linearGradient id="SVGXci6Ba6J" x1="92.88%" x2="59.841%" y1="74.122%" y2="39.704%"><stop offset="0%" class="h3xd-3bzt"/><stop offset="0%" class="h3xd-3bzt"/><stop offset="99%" class="v4700dkua"/><stop offset="100%" class="v4700dkua"/></linearGradient><linearGradient id="SVGZfms5bcW" x1="56.57%" x2="3.105%" y1="101.717%" y2="11.993%"><stop offset="0%" class="iipf5j-mn"/><stop offset="0%" class="iipf5j-mn"/><stop offset="43%" class="dtgi8tbtl"/><stop offset="99%" class="kv77ch53o"/><stop offset="100%" class="kv77ch53o"/></linearGradient><linearGradient id="SVG9Fw0PeZk" x1="30.87%" x2="92.471%" y1="35.599%" y2="100.694%"><stop offset="0%" class="q91zgcc_y"/><stop offset="0%" class="q91zgcc_y"/><stop offset="44%" class="l9c3zxbog"/><stop offset="99%" class="wqwfuj05f"/><stop offset="100%" class="wqwfuj05f"/></linearGradient><radialGradient id="SVGTXBEHcgf" cx="32.001%" cy="40.21%" r="69.573%" fx="32.001%" fy="40.21%"><stop offset="0%" class="ezidwnbja"/><stop offset="0%" class="ezidwnbja"/><stop offset="99%" class="m0lf0xtnz"/><stop offset="100%" class="m0lf0xtnz"/></radialGradient><radialGradient id="SVGIoVSAcoi" cx="13.549%" cy="40.86%" r="88.386%" fx="13.549%" fy="40.86%"><stop offset="0%" class="d1bgm_xyy"/><stop offset="0%" class="d1bgm_xyy"/><stop offset="99%" class="r70gc76fy"/><stop offset="100%" class="r70gc76fy"/></radialGradient></defs><path fill="url(#SVGp7IY8bkc)" class="atqydgwwx"/><path fill="url(#SVGUgNYzcuh)" class="k2fvn1-oh"/><path fill="url(#SVG511Aleka)" class="cpjhu7btd"/><path fill="url(#SVGuISx0ckJ)" class="zakueqb9v"/><path fill="url(#SVGp2ih7dhN)" class="gichgjb3t"/><path fill="url(#SVGVVXNPbRt)" class="coqmq67df"/><path fill="url(#SVGpaPWneGk)" class="xa7z_bbar"/><path fill="url(#SVG1WvP2bcC)" class="i76sn3bwx"/><path class="z7k5tacsh"/><path fill="url(#SVGtihA7dCK)" class="sfsdibcge"/><path fill="url(#SVG4PNQfcAN)" class="gl1vg_-fi"/><path fill="url(#SVG7JSnDYmr)" class="ysg86c-cf"/><path fill="url(#SVGXci6Ba6J)" class="j4cob2dtt"/><path class="tfa2icc-i"/><path fill="url(#SVGTXBEHcgf)" class="vcqybm9sq"/><path fill="url(#SVGIoVSAcoi)" class="jzsqdnb_u"/><path fill="url(#SVGZfms5bcW)" class="vl-goib_k"/><path fill="url(#SVG9Fw0PeZk)" class="g2phq7bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:ruby" /></template>
<style>
.anp5c3pdg {
  stop-color: var(--svg-color--900, #900);
}

.atqydgwwx {
  d: path("m197.467 167.764l-145.52 86.41l188.422-12.787L254.88 51.393z");
}

.coqmq67df {
  d: path("m248.693 82.73l-73.777-60.256l-20.544 66.418z");
}

.cpjhu7btd {
  d: path("m240.896 241.257l-118.646-9.313l-69.674 21.986z");
}

.cqcs1lp7p {
  stop-color: var(--svg-color--990c00, #990c00);
}

.d1bgm_xyy {
  stop-color: var(--svg-color--a30c00, #a30c00);
}

.ddk317bha {
  stop-color: var(--svg-color--b31301, #b31301);
}

.dpr9tb3ch {
  stop-color: var(--svg-color--e46342, #e46342);
}

.dtgi8tbtl {
  stop-color: var(--svg-color--9e100a, #9e100a);
}

.ezidwnbja {
  stop-color: var(--svg-color--a80d00, #a80d00);
}

.f4ld04byb {
  stop-color: var(--svg-color--e82609, #e82609);
}

.g2phq7bbv {
  d: path("m174.826 22.654l78.1 10.96c-4.169-17.662-16.969-29.06-38.787-32.623z");
}

.gichgjb3t {
  d: path("M180.358 188.05L153.085 81.226l-78.047 73.16z");
}

.gk6kz_ald {
  stop-color: var(--svg-color--820c01, #820c01);
}

.gl1vg_-fi {
  d: path("m52.744 253.916l29.408-97.409l97.665 31.376c-35.312 33.113-74.587 61.106-127.073 66.033");
}

.h3xd-3bzt {
  stop-color: var(--svg-color--79130d, #79130d);
}

.h8fnprbnu {
  stop-color: var(--svg-color--871101, #871101);
}

.i_f-8ebbv {
  stop-color: var(--svg-color--bf0905, #bf0905);
}

.i76sn3bwx {
  d: path("m0 203.372l18.177-33.151l-14.704-39.494z");
}

.iipf5j-mn {
  stop-color: var(--svg-color--8b2114, #8b2114);
}

.j1y0librw {
  stop-color: var(--svg-color--fb7655, #fb7655);
}

.j4cob2dtt {
  d: path("M248.847 82.833c10.035-30.282 12.35-73.725-34.966-81.791l-38.825 21.445z");
}

.jl8pcyvuf {
  stop-color: var(--svg-color--e42b1e, #e42b1e);
}

.jzsqdnb_u {
  d: path("m82.113 156.507l39.313 75.848c23.246-12.607 41.45-27.967 58.121-44.42z");
}

.k2fvn1-oh {
  d: path("M240.677 241.257L224.482 129.48l-44.113 58.25z");
}

.kv77ch53o {
  stop-color: var(--svg-color--b3100c, #b3100c);
}

.l9c3zxbog {
  stop-color: var(--svg-color--910f08, #910f08);
}

.lsv7azf7j {
  stop-color: var(--svg-color--c82410, #c82410);
}

.m0lf0xtnz {
  stop-color: var(--svg-color--7e0e08, #7e0e08);
}

.oe74w3r0p {
  stop-color: var(--svg-color--7e110b, #7e110b);
}

.oyjo3ex1c {
  stop-color: var(--svg-color--de3b20, #de3b20);
}

.q7xz9abfp {
  stop-color: var(--svg-color--911209, #911209);
}

.q91zgcc_y {
  stop-color: var(--svg-color--b31000, #b31000);
}

.q9tep7byl {
  stop-color: var(--svg-color--e4714e, #e4714e);
}

.qw5y8xbnh {
  stop-color: var(--svg-color--bf190b, #bf190b);
}

.r70gc76fy {
  stop-color: var(--svg-color--800e08, #800e08);
}

.s8aw0sl5f {
  stop-color: var(--svg-color--bd0012, #bd0012);
}

.sfsdibcge {
  d: path("M54.442 54.094c37.86-37.538 86.667-59.716 105.397-40.818c18.72 18.898-1.132 64.823-38.992 102.349c-37.86 37.525-86.062 60.925-104.78 42.027c-18.73-18.885.515-66.032 38.375-103.558");
}

.six_5zb0y {
  stop-color: var(--svg-color--8c0c01, #8c0c01);
}

.tfa2icc-i {
  fill: var(--svg-color--9e1209, #9e1209);
  d: path("M0 202.935c1.39 49.979 37.448 50.724 52.808 51.162l-35.48-82.86z");
}

.u0l4xx4ah {
  stop-color: var(--svg-color--a80d0e, #a80d0e);
}

.ug4qrab9a {
  stop-color: var(--svg-color--c82f1c, #c82f1c);
}

.v4700dkua {
  stop-color: var(--svg-color--9e120b, #9e120b);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vcqybm9sq {
  d: path("M155.232 88.777c22.667 13.932 68.35 41.912 69.276 42.426c1.44.81 19.695-30.784 23.838-48.64z");
}

.veuf6qxqw {
  stop-color: var(--svg-color--9e0c00, #9e0c00);
}

.vgglilblh {
  stop-color: var(--svg-color--be1a0d, #be1a0d);
}

.vl-goib_k {
  d: path("m17.174 171.34l-5.57 66.328c10.51 14.357 24.97 15.605 40.136 14.486c-10.973-27.311-32.894-81.92-34.566-80.814");
}

.w_afh7bgq {
  stop-color: var(--svg-color--c81f11, #c81f11);
}

.w8ttm0bgd {
  stop-color: var(--svg-color--de4024, #de4024);
}

.wqwfuj05f {
  stop-color: var(--svg-color--791c12, #791c12);
}

.wr97chdyu {
  stop-color: var(--svg-color--e57252, #e57252);
}

.wxf-xc86f {
  stop-color: var(--svg-color--a60003, #a60003);
}

.xa7z_bbar {
  d: path("M214.191.99L170.8 24.97L143.424.669z");
}

.yjb2dqbqe {
  stop-color: var(--svg-color--a31601, #a31601);
}

.ysg86c-cf {
  d: path("m155.092 88.622l25.073 99.313c29.498-31.016 55.972-64.36 68.938-105.603z");
}

.z7k5tacsh {
  fill: var(--svg-color--fff, #fff);
  d: path("m2.496 129.48l14.794 41.963l64.283-14.422l73.39-68.207l20.712-65.787L143.063 0L87.618 20.75c-17.469 16.248-51.366 48.396-52.588 49c-1.21.618-22.384 40.639-32.534 59.73");
}

.zakueqb9v {
  d: path("m52.744 253.955l29.64-97.1L17.16 170.8z");
}

</style>
