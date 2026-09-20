<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yzevdc47s"/><path class="acruuobfm"/><path class="u349h8yns"/><path class="skb22ysla"/><path class="q-7g8y78e"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:srx-background" /></template>
<style>
.acruuobfm {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.444 10V6L4.89 8zm0 4v-4L4.89 12zm0 4v-4L4.89 16zm10.667-2v-4l-3.555 2zm-3.555-2v-4L12 12zm0 4v-4L12 16z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-7g8y78e {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.556 10V6l3.555 2zm0 4v-4l3.555 2zm0 4v-4l3.555 2z");
}

.skb22ysla {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.444 10V6L12 8zm0 4v-4L12 12zM12 20v-4l3.556 2zm-7.111-8V8l3.555 2zm0 4v-4l3.555 2zM12 8V4l3.556 2z");
}

.u349h8yns {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20v-4l-3.556 2zm7.111-8V8l-3.555 2zM12 8V4L8.444 6z");
}

.yzevdc47s {
  fill: var(--svg-color--e23c25, #e23c25);
  d: path("M24 0H0v24h24z");
}

</style>
