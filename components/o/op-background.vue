<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="en6va-rjv"/><path clip-rule="evenodd" class="h3_8vxyya"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:op-background" /></template>
<style>
.en6va-rjv {
  fill: var(--svg-color--fe0420, #fe0420);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.h3_8vxyya {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M4.859 15.378Q5.729 16 7.09 16q1.65 0 2.633-.744q.985-.756 1.386-2.278q.24-.933.412-1.922q.057-.356.057-.59q0-.777-.4-1.333a2.4 2.4 0 0 0-1.1-.844Q9.381 7.999 8.5 8q-3.24 0-4.018 3.056a36 36 0 0 0-.424 1.922a4 4 0 0 0-.057.6q0 1.166.859 1.8m4.133-2.467c-.22.85-.824 1.405-1.74 1.405c-.907 0-1.217-.613-1.054-1.405q.206-1.077.412-1.822c.237-.919.793-1.405 1.74-1.405c.903 0 1.2.605 1.042 1.405a26 26 0 0 1-.4 1.822m3.469 3.009q.066.08.19.08h1.514a.33.33 0 0 0 .211-.08a.33.33 0 0 0 .123-.206l.478-2.24h1.541c.973 0 1.734-.472 2.29-.891q.848-.63 1.125-1.943q.067-.309.067-.594q0-.995-.757-1.52Q18.496 8 17.26 8h-2.963a.34.34 0 0 0-.211.08a.33.33 0 0 0-.123.206l-1.537 7.428a.28.28 0 0 0 .034.206m5.412-5.303c-.139.612-.672 1.172-1.299 1.172h-1.28l.44-2.105h1.337c.455 0 .835.09.835.59q0 .15-.033.343");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
