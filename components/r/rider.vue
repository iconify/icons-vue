<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGxD1wR08k" x1="90.832%" x2="-19.123%" y1="81.803%" y2="19.04%"><stop offset="0%" class="gze0ohbmc"/><stop offset="48%" class="gze0ohbmc"/><stop offset="94%" class="li_ovhbqw"/></linearGradient><linearGradient id="SVGd4VpRdPz" x1="35.983%" x2="53.7%" y1="7.271%" y2="92.994%"><stop offset="14%" class="r_lf9ybqi"/><stop offset="48%" class="gze0ohbmc"/><stop offset="96%" class="r_lf9ybqi"/></linearGradient><linearGradient id="SVGRbH9nbrm" x1="39.545%" x2="56.938%" y1="11.352%" y2="91.694%"><stop offset="28%" class="gze0ohbmc"/><stop offset="97%" class="li_ovhbqw"/></linearGradient></defs><path fill="url(#SVGxD1wR08k)" class="qk0yw50cv"/><path fill="url(#SVGd4VpRdPz)" class="r8ov1zbhg"/><path fill="url(#SVGRbH9nbrm)" class="vm8-ur85k"/><path class="pn_7tebcp"/><path class="k182hsk6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:rider" /></template>
<style>
.gze0ohbmc {
  stop-color: var(--svg-color--dd1265, #dd1265);
}

.k182hsk6x {
  fill: var(--svg-color--fff, #fff);
  d: path("M67.947 178.08h60v10h-60zM68 68.107h27.467a24 24 0 0 1 17.52 6.106a18.88 18.88 0 0 1 5.188 12.957l-.015.963a18.67 18.67 0 0 1-12.907 18.667l14.72 21.493H104.48L91.6 109.04H81.333v19.253H68zM94.667 97.44c6.238 0 9.91-3.214 10.147-8.005l.013-.662c0-5.68-3.947-8.613-10.4-8.613H81.333v17.28zm34.48-29.333h23.466c18.616 0 31.596 12.59 31.991 29.141l.01.965c0 16.934-13.067 30.08-32 30.08h-23.467zm13.333 11.946v36.267h10.24a17.147 17.147 0 0 0 18.155-17.206l-.022-.927a17.307 17.307 0 0 0-18.133-18.16z");
}

.li_ovhbqw {
  stop-color: var(--svg-color--fdb60d, #fdb60d);
}

.pn_7tebcp {
  d: path("M48 48.32h160v160H48z");
}

.qk0yw50cv {
  d: path("M256 99.6L76.533 0l120.16 178.533l24.694-16.186z");
}

.r_lf9ybqi {
  stop-color: var(--svg-color--087cfa, #087cfa);
}

.r8ov1zbhg {
  d: path("m184.4 58.987l-22.48-54.96l-49.733 48.96l20.346 177.653L180.72 256L256 212.027z");
}

.vm8-ur85k {
  d: path("M76.533 0L0 51.547L28.453 227.36l73.387 28.213l94.853-77.04z");
}

</style>
