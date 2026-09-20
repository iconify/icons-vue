<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="cv7_f3e6c"/><path class="a927ojbxe"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:steem-background" /></template>
<style>
.a927ojbxe {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.7 5.73c.177.033-.258 1.186-.016 2.502c.21 1.13 2.825 5.52 2.72 7.022c-.081.952-2.236 3.163-2.462 3.019c-.242-.073.654-1.575.323-2.825c-.395-1.47-2.696-5.246-2.696-6.917c0-1.219 1.978-2.881 2.131-2.8m4.923-1.727c.227.04-.322 1.51-.016 3.196c.267 1.445 3.608 7.038 3.47 8.959c-.104 1.202-2.849 4.02-3.139 3.833c-.315-.08.831-2.001.404-3.6c-.485-1.863-3.43-6.69-3.43-8.813c0-1.565 2.518-3.672 2.72-3.575zm5.093 1.727c.177.033-.258 1.186-.016 2.502c.21 1.13 2.825 5.52 2.728 7.022c-.08.952-2.236 3.163-2.47 3.019c-.242-.073.654-1.575.323-2.825c-.388-1.47-2.696-5.246-2.696-6.917c0-1.219 1.978-2.881 2.131-2.8");
}

.cv7_f3e6c {
  fill: var(--svg-color--171fc9, #171fc9);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
