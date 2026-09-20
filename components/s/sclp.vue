<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGFbQXKbjM)" class="yy-21-bqi"/><path fill="url(#SVGZzDq9csh)" class="fywthcb-h"/><defs><linearGradient id="SVGFbQXKbjM" x1="17.767" x2="-4.099" y1="-3.604" y2="58.547" gradientUnits="userSpaceOnUse"><stop class="tkk09cb1k"/><stop offset=".38" class="c7nqqjb5v"/><stop offset="1" class="q4qrdtwyi"/></linearGradient><linearGradient id="SVGZzDq9csh" x1="18.744" x2="-5.314" y1="-1.382" y2="51.148" gradientUnits="userSpaceOnUse"><stop class="tkk09cb1k"/><stop offset=".38" class="c7nqqjb5v"/><stop offset="1" class="q4qrdtwyi"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sclp" /></template>
<style>
.c7nqqjb5v {
  stop-color: var(--svg-color--3a8afa, #3a8afa);
}

.ft5dv1b6b {
  fill: none;
}

.fywthcb-h {
  d: path("M18.225 18.187c-3.028 3.023-6.59 3.568-9.809 1.827l1.281-1.334l2.933-3.033l2.916-2.917a.78.78 0 0 0 0-1.09l-2.927-2.928l3.594-3.758l.318-.328c.529.37 1.058.82 1.561 1.323c3.774 3.764 3.933 8.433.133 12.238");
}

.q4qrdtwyi {
  stop-color: var(--svg-color--1a6af4, #1a6af4);
}

.tkk09cb1k {
  stop-color: var(--svg-color--00deca, #00deca);
}

.yy-21-bqi {
  d: path("m15.674 4.077l-4.288 4.409a.3.3 0 0 0-.042.037L8.23 11.635a.77.77 0 0 0 0 1.09l2.948 2.95l-3.63 3.81a11 11 0 0 1-1.631-1.37C2.112 14.318 1.98 9.618 5.812 5.78c3.038-3.038 6.622-3.552 9.862-1.704");
}

</style>
