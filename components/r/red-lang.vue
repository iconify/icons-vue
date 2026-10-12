<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGMLBKVdeO" x1=".103%" x2="99.979%" y1="50%" y2="50%"><stop offset="0%" class="oyey6ql1o"/><stop offset="100%" class="smzaobguw"/></linearGradient><linearGradient id="SVGJVhugdVH" x1="0%" x2="100%" y1="50%" y2="50%"><stop offset="0%" class="pkl08ubxc"/><stop offset="58.34%" class="y_6-cwvsq"/><stop offset="100%" class="q8q3clbbp"/></linearGradient><linearGradient id="SVGK0wObFwM" x1="0%" x2="99.897%" y1="50%" y2="50%"><stop offset="0%" class="c7l6a6bqu"/><stop offset="61.21%" class="v3dhx9bkq"/><stop offset="100%" class="gfif-jskx"/></linearGradient><linearGradient id="SVG8tK14byU" x1="0%" x2="100%" y1="50%" y2="50%"><stop offset="0%" class="p_vy-d1vm"/><stop offset="56.29%" class="enanyz0nq"/><stop offset="100%" class="rjkjfacro"/></linearGradient></defs><path fill="url(#SVGMLBKVdeO)" class="w8a21ublb"/><path fill="url(#SVGJVhugdVH)" class="gtp3lwbqn"/><path fill="url(#SVGK0wObFwM)" class="lj2dz4bft"/><path fill="url(#SVGJVhugdVH)" class="e7mrjqbrp"/><path fill="url(#SVG8tK14byU)" class="s7h40mmry"/><path fill="url(#SVG8tK14byU)" class="qagtvk-oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:red-lang" /></template>
<style>
.c7l6a6bqu {
  stop-color: var(--svg-color--e8a333, #e8a333);
}

.e7mrjqbrp {
  d: path("M220.315 136.663L128 184.76V256l128-66.586z");
}

.enanyz0nq {
  stop-color: var(--svg-color--d01d19, #d01d19);
}

.gfif-jskx {
  stop-color: var(--svg-color--ab762f, #ab762f);
}

.gtp3lwbqn {
  d: path("M128 92.315v71.37l81.842-42.667l-35.684-52.751z");
}

.lj2dz4bft {
  d: path("m128 71.24l35.685-18.488L128 0z");
}

.oyey6ql1o {
  stop-color: var(--svg-color--eea831, #eea831);
}

.p_vy-d1vm {
  stop-color: var(--svg-color--ae2524, #ae2524);
}

.pkl08ubxc {
  stop-color: var(--svg-color--b32629, #b32629);
}

.q8q3clbbp {
  stop-color: var(--svg-color--7a1a1d, #7a1a1d);
}

.qagtvk-oj {
  d: path("m81.842 68.267l-35.684 52.751L128 163.685v-71.37z");
}

.rjkjfacro {
  stop-color: var(--svg-color--ed1913, #ed1913);
}

.s7h40mmry {
  d: path("M0 189.414L128 256v-71.24l-92.315-48.097z");
}

.smzaobguw {
  stop-color: var(--svg-color--ffc929, #ffc929);
}

.v3dhx9bkq {
  stop-color: var(--svg-color--c68931, #c68931);
}

.w8a21ublb {
  d: path("M128 71.24V0L92.315 52.752z");
}

.y_6-cwvsq {
  stop-color: var(--svg-color--8c1e21, #8c1e21);
}

</style>
