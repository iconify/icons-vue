<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":193};
const content = `<defs><linearGradient id="SVGKP5aFcoo" x1="49.385%" x2="50.286%" y1="49.503%" y2="50.417%"><stop offset="0%"/><stop offset="100%" class="k05n1gbkm"/></linearGradient><linearGradient id="SVGAFu28bFT" x1="50.147%" x2="49.946%" y1="49.935%" y2="50.142%"><stop offset="0%"/><stop offset="100%" class="k05n1gbkm"/></linearGradient><linearGradient id="SVGpVOGjdgM" x1="81.503%" x2="93.734%" y1="46.547%" y2="50.202%"><stop offset="0%" class="w0nl4mfrq"/><stop offset="44.42%" class="ruaue58hw"/><stop offset="64.06%" class="i_8iqmb0z"/><stop offset="100%" class="agq5extxc"/></linearGradient><linearGradient id="SVGK4pKlbDQ" x1="63.475%" x2="41.388%" y1="61.32%" y2="43.414%"><stop offset="0%" class="pn7pd_a_c"/><stop offset="100%" class="a8-updb-w"/></linearGradient><linearGradient id="SVG4dpb5dDp" x1="50.894%" x2="49.16%" y1="51.117%" y2="49.274%"><stop offset="0%" class="sde8bid2d"/><stop offset="13.34%" class="kmw-5ce2l"/><stop offset="29.45%" class="opgnp9rna"/><stop offset="50.21%" class="f9qhwgbzx"/><stop offset="69.66%" class="kr-09eboz"/><stop offset="86.31%" class="she65ac6d"/><stop offset="100%" class="wk1loj6jn"/></linearGradient><linearGradient id="SVGk6D6PdyS" x1="47.423%" x2="22.315%" y1="28.937%" y2="77.493%"><stop offset="8.81%" class="qbqkj5u9f"/><stop offset="48.29%" class="ezp2cl61v"/><stop offset="77.92%" class="k7ygktcyp"/></linearGradient><linearGradient id="SVGgOaZ7dWB" x1="41.147%" x2="56.579%" y1="57.288%" y2="44.95%"><stop offset="3.27%" class="a8-updb-w"/><stop offset="100%" class="pn7pd_a_c"/></linearGradient><linearGradient id="SVG6GBkle7H" x1="49.624%" x2="50.677%" y1="50.47%" y2="49.223%"><stop offset="0%" class="tpzrw1vza"/><stop offset="8.6%" class="kyznz5pqw"/><stop offset="19.77%" class="sy_gfq40q"/><stop offset="58.28%" class="yenoxibpl"/><stop offset="77.71%" class="a8-updb-w"/><stop offset="92.39%" class="q4as12-wu"/></linearGradient><linearGradient id="SVGdEDvKd3a" x1="8.211%" x2="93.243%" y1="50.006%" y2="50.006%"><stop offset="0%" class="wo60yyxlp"/><stop offset="49.29%" class="u8xn9lp1i"/><stop offset="50%" class="zpdzwlrtw"/><stop offset="52.97%" class="aflx-iv2v"/><stop offset="100%" class="wo60yyxlp"/></linearGradient><linearGradient id="SVGh09ZSdhR" x1="49.901%" x2="49.998%" y1="50.091%" y2="49.994%"><stop offset="0%" class="a_jx0jb_k"/><stop offset="23.97%" class="wj53x-bea"/><stop offset="100%" class="ouyswbc0t"/></linearGradient><linearGradient id="SVG935yLewp" x1="51.38%" x2="48.714%" y1="48.236%" y2="51.568%"><stop offset="4.76%" class="qcmii1bow"/><stop offset="41.56%" class="lqxvo2bjw"/><stop offset="81.35%" class="lnfhfmb8r"/></linearGradient><linearGradient id="SVGoLXLCdfc" x1="63.039%" x2="24.984%" y1="46.844%" y2="8.907%"><stop offset="0%" class="fsmnxccxz"/><stop offset="43.11%" class="vbygvc10b"/><stop offset="44.07%" class="e4q6n_bsv"/><stop offset="87.37%" class="vlybygv3i"/><stop offset="100%" class="zfx6--g2v"/></linearGradient><linearGradient id="SVGGyKSifyT" x1="49.999%" x2="50.108%" y1="50.004%" y2="50.114%"><stop offset="0%" class="ouyswbc0t"/><stop offset="100%" class="a_jx0jb_k"/></linearGradient><linearGradient id="SVGcfAQvhIf" x1="45.656%" x2="50.475%" y1="62.623%" y2="33.538%"><stop offset="0%" class="mzkf_gbse"/><stop offset="38.57%" class="g786bubhr"/><stop offset="45.57%" class="xeest-brn"/><stop offset="62.36%" class="mzkf_gbse"/><stop offset="100%" class="tlt_zybav"/></linearGradient></defs><path fill="url(#SVGKP5aFcoo)" class="lt0to1dtd"/><path fill="url(#SVGAFu28bFT)" class="wfdds2byc"/><path class="v-hcwpbxb"/><path fill="url(#SVGpVOGjdgM)" class="eln44-z1m"/><path fill="url(#SVGK4pKlbDQ)" class="vs9_nbcij"/><path fill="url(#SVG4dpb5dDp)" class="ayp127m3j"/><path class="snm5sm1vu"/><path fill="url(#SVGk6D6PdyS)" class="hbfg68i7o"/><path fill="url(#SVGgOaZ7dWB)" class="dqr7wz8-v"/><path fill="url(#SVG6GBkle7H)" class="nw-pkopsc"/><path fill="url(#SVGdEDvKd3a)" class="b8ea02z_b"/><path class="ffjj40btv"/><path class="zyuv02bpm"/><path fill="url(#SVGh09ZSdhR)" class="v8x-rvbvb"/><path class="ed9xg0b2k"/><path fill="url(#SVG935yLewp)" class="nbdg5i7zj"/><path class="urhxdlpxc"/><path fill="url(#SVGoLXLCdfc)" class="lla9k0g1k"/><path class="c6ctodh9f"/><path class="esiwc-t-v"/><path class="lsxjvdidp"/><path fill="url(#SVGGyKSifyT)" class="ad-93xbpo"/><path class="uylbjfx3w"/><path class="eojo_8tln"/><path fill="url(#SVGcfAQvhIf)" class="la9xclbpl"/><path class="y7n7c2bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:parcel-icon" /></template>
<style>
.a_jx0jb_k {
  stop-color: var(--svg-color--322214, #322214);
}

.a8-updb-w {
  stop-color: var(--svg-color--e4af76, #e4af76);
}

.ad-93xbpo {
  d: path("M211.952 146.335v.04c-.06.51-.3.66-.81 1.01l-70.077 44.358c-.1.07-.21.11-.31.14v-.26z");
  opacity: var(--svg-opacity--0-54, 0.54);
}

.aflx-iv2v {
  stop-color: var(--svg-color--743f1a, #743f1a);
  stop-opacity: 0.847;
}

.agq5extxc {
  stop-color: var(--svg-color--964e23, #964e23);
}

.ayp127m3j {
  d: path("M119.35 46.619L67.102 65.398l-8.15-2.09l59.028-21.22l.55.82c.6.88.66 1.42.66 1.81h.15z");
}

.b8ea02z_b {
  d: path("M121.055 44.809v40.508l-1.47-.95h-.01l-1.93-1.26V45.049l1.51-.54h.51z");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.c6ctodh9f {
  fill: var(--svg-color--d4a271, #d4a271);
  d: path("M141.434 99.977c-.41.01-.71.57-.71 1.06c-.01.04-.08.03-.09 0c-.08-1.09-.53-2.31-1.12-2.74l-34.868-22.48l.34-.91h.01l34.589 22.41c1.29.81 1.39 1.69 1.4 2.49c0 .01 0 .03.01.04c.04.19.28.12.44.13");
}

.dqr7wz8-v {
  d: path("m241.1 21.81l-11.059 18.309l-40.438 17.19l-3.98 1.69l-65.948-14.49c-.04-.51.31-1.67.69-2.41c.08-.16.16-.29.24-.4l25.15-36.579c.06-.09.09-.13.22-.11l94.966 16.34z");
}

.e4q6n_bsv {
  stop-color: var(--svg-color--976a40, #976a40);
}

.ed9xg0b2k {
  fill: var(--svg-color--322214, #322214);
  d: path("m97.406 135.865l37.119 12.14l-.09 36.198l-36.429-13.38zm18.6 24.32l.09 16.769l17.978 6.604v-17.094zm5.311 5.417l3.633 5.782l3.559-3.118l.62.707l-3.673 3.217l3.681 5.858l-.533.335l-3.628-5.773l-3.541 3.104l-.62-.707l3.655-3.203l-3.686-5.867zm10.698 6.512v1.65l.95.31v1.86l-.95-.38v1.5l-2.08-3.16zm-3.2-2.01l.73.23v6.59l-.73-.26zm-30.679-16.13l.27 16.51l17.18 6.28l-.1-16.73zm26.86 19.68l1.88 3.03l-3.75-1.36zm2.899-2.78v4.3l-1.95-2.75zm-7.44-3.83l.72.24v6.58l-.72-.25zm1.62 1.77l1.86 2.87l-1.86 1.43zm-15.54-7.97l.71.23l.002.422c2.114.85 4.202 2.97 5.209 6.268c-.66-1.11-1.24-1.32-2.27-.97c-.38-.79-1.5-1.21-2.17-.79a1.93 1.93 0 0 0-.746-.776l.036 6.276c0 .58-.4 1.1-1.39.9c-.9-.22-1.27-.91-1.17-2.09l.5.08c0 .79.06 1.24.66 1.38c.51.12.74-.07.74-.54l-.066-6.225c-.284-.02-.547.05-.734.215c-.23-.58-1.32-1.36-2.14-.78c-.58-.92-1.67-1.27-2.28-.6c.779-2.355 2.894-3.18 5.113-2.585zm11.38 6.13l2.03 3.2l-2.01 1.67l.04-1.57l-.98-.23v-1.82l.92.34zm5.15.69l3.8 1.38l-1.9 1.67zm-7.09-25.2l.04 17.1l18.07 6.3v-17.47zm3.37 14.77l10.8 3.69v2.15l-10.8-3.72zm-9.338 4.069l.039.011c.07.07.07.82-.16.99a.41.41 0 0 1-.42-.05c-.14-.11-.22-.27-.16-.51s.66-.5.74-.43zm1-1.71l.039.011c.08.07.08.82-.16.99a.41.41 0 0 1-.42-.05c-.14-.11-.22-.27-.16-.51s.66-.5.74-.43zm-2.8-.07l.039.011c.08.07.08.82-.16.99a.41.41 0 0 1-.42-.05c-.14-.11-.22-.27-.16-.51s.66-.5.74-.43zm-2.83-.41l.039.011c.08.07.08.82-.16.99a.41.41 0 0 1-.42-.05c-.14-.11-.22-.27-.16-.51s.66-.5.74-.43zm22.308-11.228l2.62 5.17l-1.79-.61v7.49l-1.79-.62l.01-7.43l-1.78-.58zm-29.889-11.38l.31 16.87l17.39 5.98l-.15-17.09zm23.98 9.41l2.62 5.17l-1.79-.61v7.49l-1.79-.62l.02-7.43l-1.79-.58zm-20.09-6.02l1.42.47l.66 2.39l-.74-.05l2.11 5.1l-1.09-4.2l.62-.01l-.63-2.93l7.33 2.42v4.03c0 1.53-1.66 3.46-4 2.5l.01 4.05l3.36 2.16l-8.13-2.82l3.27.16l-.06-4.01c-2.32-.69-4-3.48-4-5.18z");
}

.eln44-z1m {
  d: path("M119.585 84.367h-.01l-14.579-9.449l-41.098-10.54l55.257-19.869l.15-.29v.29z");
}

.eojo_8tln {
  fill: var(--svg-color--d7aa77, #d7aa77);
  d: path("m183.733 60.838l-39.589 36.799c-1.12 1.07-1.86 2.67-1.83 3.5c-.02.04-.12.07-.16 0c.05-.64-.36-1.08-.66-1.15c.15.02.29.07.33-.12c.02-.12.05-.26.1-.41c.04-.13.1-.27.17-.42c.24-.54.63-1.16 1.11-1.64l39.929-37.339z");
}

.esiwc-t-v {
  fill: var(--svg-color--deb37e, #deb37e);
  d: path("m104.986 74.918l-.34.9L0 48.809l.33-.74z");
}

.ezp2cl61v {
  stop-color: var(--svg-color--9a5227, #9a5227);
}

.f9qhwgbzx {
  stop-color: var(--svg-color--dea167, #dea167);
}

.ffjj40btv {
  fill: var(--svg-color--bf9064, #bf9064);
  d: path("m140.195 191.843l-95.867-35.769c-.54-.23-.62-.74-.65-1.37c0 0-4.12-81.696-4.13-81.706c-.01-.21.25-.34.23-.47c-.07-.31-.66-1.48-.85-1.6L0 48.808l.33-.75l104.666 26.86l34.589 22.409c1.29.8 1.39 1.69 1.4 2.49c.01.22.27.15.45.16s.35.1.39-.11c.09-.61.61-1.71 1.38-2.47l39.928-37.339L255.54 29.28l.44.61l-39.088 34.349c-.76.76-1.11 1.69-.96 2.07l-4 80.067c-.06.51-.3.66-.81 1.01l-70.077 44.358c-.28.18-.58.23-.85.1");
}

.fsmnxccxz {
  stop-color: var(--svg-color--845f35, #845f35);
}

.g786bubhr {
  stop-color: var(--svg-color--ae7f53, #ae7f53);
}

.hbfg68i7o {
  d: path("m185.613 59.008l-2.47 1.05l-39.929 37.339c-.77.77-1.29 1.87-1.38 2.48c-.04.21-.22.12-.39.11c-.18-.01-.43.06-.45-.16c-.02-.8-.11-1.69-1.4-2.49l-20.009-12.97l-.27-39.848v-.29l.37.29z");
}

.i_8iqmb0z {
  stop-color: var(--svg-color--a05728, #a05728);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7ygktcyp {
  stop-color: var(--svg-color--8d4520, #8d4520);
}

.kmw-5ce2l {
  stop-color: var(--svg-color--c37a45, #c37a45);
}

.kr-09eboz {
  stop-color: var(--svg-color--e8af73, #e8af73);
}

.kyznz5pqw {
  stop-color: var(--svg-color--af6a38, #af6a38);
}

.la9xclbpl {
  d: path("M175.003 105.476c0 .11.05.16.12.13l11.89-6.1c.02-.01.03-.03.04-.07l.66-19.489c.02-1.07.62-2.13 1.44-2.86L228.64 41.6l-12.02 5.15l-39.688 35.958c-1.02 1-1.37 2.18-1.39 3.18z");
}

.lla9k0g1k {
  d: path("M95.996 109.136c.11.03.15.04.15-.05l-.38-20.339c-.03-.69-.2-2.05-1.03-2.6L57.868 63.748l-17.28-4.46l37.469 22.39c.94.62 1.02 1.78 1.06 2.64l.54 19.778c0 .1.02.12.09.15z");
}

.lnfhfmb8r {
  stop-color: var(--svg-color--b5875b, #b5875b);
}

.lqxvo2bjw {
  stop-color: var(--svg-color--ba8c5e, #ba8c5e);
}

.lsxjvdidp {
  fill: var(--svg-color--dbad77, #dbad77);
  d: path("m215.952 66.298l-4 80.067c-.06.51-.3.66-.81 1.01l-70.077 44.358c-.1.07-.21.11-.31.14l.69-91.906c.18.01.35.1.39-.11c0-.03.01-.05.01-.08l74.087-33.57c0 .05.01.07.02.09");
}

.lt0to1dtd {
  d: path("m140.515 191.333l70.257-44.428c.26-.16.6-.09.76.17s.09.6-.17.76l-70.487 44.568c-.09.06-.19.09-.29.09z");
}

.mzkf_gbse {
  stop-color: var(--svg-color--a9794b, #a9794b);
}

.nbdg5i7zj {
  d: path("M141.434 99.977c-.4.01-.7.54-.71 1.02l-.09.04l-101.096-28.04c-.01-.19.21-.31.23-.43q.015-.015 0-.03c-.07-.31-.66-1.48-.85-1.6L0 48.81l.33-.75l104.656 26.849h.01l34.589 22.409c1.29.81 1.39 1.69 1.4 2.49c0 .01 0 .03.01.04c.04.19.28.12.44.13");
}

.nw-pkopsc {
  d: path("m189.603 57.308l-6.45 2.74l-.83.8l-63.018-13.93l.29-2.42h.08c-.04-.51.31-1.67.69-2.41z");
}

.opgnp9rna {
  stop-color: var(--svg-color--d08d55, #d08d55);
}

.ouyswbc0t {
  stop-color: var(--svg-color--322214, #322214);
  stop-opacity: 0;
}

.pn7pd_a_c {
  stop-color: var(--svg-color--e9b880, #e9b880);
}

.q4as12-wu {
  stop-color: var(--svg-color--e4af76, #e4af76);
  stop-opacity: 0;
}

.qbqkj5u9f {
  stop-color: var(--svg-color--af6938, #af6938);
}

.qcmii1bow {
  stop-color: var(--svg-color--c69866, #c69866);
}

.ruaue58hw {
  stop-color: var(--svg-color--bb713d, #bb713d);
}

.sde8bid2d {
  stop-color: var(--svg-color--c37a45, #c37a45);
  stop-opacity: 0;
}

.she65ac6d {
  stop-color: var(--svg-color--ecb477, #ecb477);
}

.snm5sm1vu {
  fill: var(--svg-color--d2a679, #d2a679);
  d: path("m30.249 55.738l-.74-.19L7.72 21.7l.33-.38z");
}

.sy_gfq40q {
  stop-color: var(--svg-color--b87542, #b87542);
}

.tlt_zybav {
  stop-color: var(--svg-color--b2875d, #b2875d);
}

.tpzrw1vza {
  stop-color: var(--svg-color--af6a38, #af6a38);
  stop-opacity: 0;
}

.u8xn9lp1i {
  stop-color: var(--svg-color--743f1a, #743f1a);
  stop-opacity: 0.887;
}

.urhxdlpxc {
  fill: var(--svg-color--cd9c6b, #cd9c6b);
  d: path("M216.902 64.228c-.76.76-1.11 1.69-.96 2.07l-73.628 34.839l-.15-.12c-.01-.58-.38-.97-.66-1.03c.15.02.29.07.33-.12c.02-.12.05-.26.1-.41c.04-.13.1-.27.17-.42c.21-.48.53-1 .94-1.46c.06-.06.12-.13.18-.19l39.929-37.339L255.56 29.27l.44.61z");
}

.uylbjfx3w {
  fill: var(--svg-color--322214, #322214);
  d: path("m210.642 111.496l-1.6 32.599l-23.3 14.51l1.2-33.93zm-12.46 23.6l-11.58 6.809l-.55 16.05l11.53-7.17zm-5.53 6.889l-.02.54c1.383-.69 2.69-.21 3.24 2.08c-.38-.53-1.07-.32-1.53.76c-.21-.45-1.28-.08-1.44.86c-.085-.153-.238-.209-.414-.189l-.255 6.189c-.02.53-.05 1.1-.72 1.51c-.31.14-1.13.25-1.02-.9l.39-.3c-.03.73.16.95.56.71c.48-.29.39-.75.41-1.18l.215-5.864a1.4 1.4 0 0 0-.605.894c-.12-.36-1.28-.14-1.42.89c-.33-.44-1.23-.01-1.57 1.1c.626-2.883 2.178-5.276 3.723-6.306l.017-.474zm16.9-13.61l-11.04 6.53l-.61 15.73l10.92-6.87zm-3.41 5.3l.32.3l-2.406 5.458l1.986 2.742l-.32.68l-1.98-2.71l-2.38 5.4l-.33-.3l2.424-5.491l-2.054-2.809l.36-.68l2.01 2.775zm-6.72 6.27l1.25 1.52l-1.33 2.86v-1.26l-.56.34l.03-1.63l.56-.33zm2.16-1.98l-.26 6.03l-.45.3l.25-6.01zm2.11 3.15l1.07 1.41l-2.3 1.4zm-12.25.44c.05 0 .02.69-.15 1.03c-.06.12-.17.25-.26.26s-.13-.09-.08-.35s.44-.94.49-.94m10.64-2.77l1.06 1.31l-1.24 2.45zm-7.6 1.52c.04.01.01.7-.15 1.03c-.06.12-.17.25-.26.26s-.13-.09-.08-.35s.44-.94.49-.94m4.44-21.84l-11.7 6.56l-.61 16.37l11.61-6.84zm7.71 16.43l-.28 6.02l-.4.26l.27-6.01zm-13.25 4.96c.05 0 .02.69-.15 1.03c-.06.12-.17.25-.26.26s-.13-.09-.08-.35s.44-.94.49-.94m12.22-3.21l-.16 3.84l-1.04-1.24zm2.48-1.83l-.06 1.48l.58-.32l-.07 1.64l-.56.33l-.02 1.35l-1.21-1.45zm-12.83 3.06c.05 0 .02.69-.15 1.03c-.06.12-.17.25-.26.26s-.13-.09-.08-.35s.44-.94.49-.94m9.78-2.32l-1.24 2.84l-1.07-1.45zm-8.83-13.61l-.15 4.12c-.06 1.4-1.18 3.94-2.85 5l-.18 3.89l2.23-.48l-5.43 3.14l2.26-2.15l.12-3.82c-1.45.83-2.61-.71-2.54-2.27l.13-3.78l.98-.53l.32 1.82l-.53.43l1.17 3.39l-.45-3.09l.4-.46l-.31-2.43zm14.2-9.859l-11.2 6.26l-.7 16.09l11.1-6.64zm-2.92 13.87l-.14 1.91l-6.56 3.88l.09-1.93zm-4.64-8.25l1.45 3.06l-1.09.61l-.33 6.87l-1.04.6l.2-6.87l-1.05.63zm3.64-2.02l1.41 3.01l-1.16.65l-.24 6.82l-1.11.62l.35-6.87l-1.09.62z");
}

.v-hcwpbxb {
  fill: var(--svg-color--e8b67f, #e8b67f);
  d: path("m241.1 21.81l-11.059 18.309l-44.428 18.89l-2.47 1.05l-39.929 37.338c-.77.77-1.29 1.87-1.38 2.48c-.04.21-.22.12-.39.11c-.18-.01-.43.06-.45-.16c-.02-.8-.11-1.69-1.4-2.49l-20.009-12.96l-14.59-9.46l-41.097-10.539l-34.4-8.82L7.71 21.71l.33-.38l.02-.03L89.857.04c.12-.04.14-.02.19.05l27.898 41.789l.55.82c.6.88.66 1.42.66 1.81h.51v-.09c0-.04 0-.09.01-.14c0-.03.01-.06.01-.1c.01-.04.01-.08.02-.12s.01-.08.02-.13c.03-.14.07-.3.11-.46c.01-.05.03-.1.04-.14c.05-.16.1-.33.16-.49c.03-.06.05-.13.08-.19c.08-.2.16-.38.25-.54c.08-.16.16-.29.24-.4l25.15-36.579c.06-.09.09-.13.22-.11l94.966 16.34z");
}

.v8x-rvbvb {
  d: path("M140.755 191.613v.26a.83.83 0 0 1-.56-.04l-95.867-35.759c-.38-.16-.53-.47-.6-.85z");
  opacity: var(--svg-opacity--0-54, 0.54);
}

.vbygvc10b {
  stop-color: var(--svg-color--91673c, #91673c);
}

.vlybygv3i {
  stop-color: var(--svg-color--986b40, #986b40);
}

.vs9_nbcij {
  d: path("M119.155 44.509L63.898 64.368l-4.98-1.28l-29.42-7.55L7.71 21.69l.35-.41L89.857.02c.12-.04.14-.02.19.05l27.898 41.789l.55.82c.6.9.66 1.44.66 1.83");
}

.w0nl4mfrq {
  stop-color: var(--svg-color--c37a44, #c37a44);
}

.wfdds2byc {
  d: path("M140.585 192.493c-.06 0-.13-.01-.19-.03l-95.787-35.699a.543.543 0 0 1-.32-.71c.11-.29.42-.43.71-.32l95.537 35.599z");
}

.wj53x-bea {
  stop-color: var(--svg-color--322314, #322314);
  stop-opacity: 0.989;
}

.wk1loj6jn {
  stop-color: var(--svg-color--ecb477, #ecb477);
  stop-opacity: 0;
}

.wo60yyxlp {
  stop-color: var(--svg-color--743f1a, #743f1a);
  stop-opacity: 0;
}

.xeest-brn {
  stop-color: var(--svg-color--ac7d50, #ac7d50);
}

.y7n7c2bsa {
  fill: var(--svg-color--f8ce93, #f8ce93);
  d: path("m183.733 60.838l72.257-30.959l-.44-.6l-72.407 30.769z");
}

.yenoxibpl {
  stop-color: var(--svg-color--d59c66, #d59c66);
}

.zfx6--g2v {
  stop-color: var(--svg-color--ab8157, #ab8157);
}

.zpdzwlrtw {
  stop-color: var(--svg-color--743f1a, #743f1a);
  stop-opacity: 0.9;
}

.zyuv02bpm {
  fill: var(--svg-color--bd8f63, #bd8f63);
  d: path("m141.434 99.977l-.69 91.906a.83.83 0 0 1-.56-.04l-95.866-35.759c-.54-.23-.62-.75-.65-1.37l-4.13-81.706v-.02c0-.02 0-.04.01-.06c0-.02.01-.03.02-.04c.01-.02.02-.03.03-.05s.02-.03.03-.05c.04-.06.1-.12.12-.17c.01-.01.01-.02.01-.03v-.01l101.237 27.279c.04.18.28.11.44.12");
}

</style>
