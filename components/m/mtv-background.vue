<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="c9ybii31p"/><path class="s-uxhdv6r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mtv-background" /></template>
<style>
.c9ybii31p {
  fill: var(--svg-color--8ae2d8, #8ae2d8);
  d: path("m4.325 5.122l6.202 3.475l-1.46.82c-.11.06-.25.025-.307 0l-2.837-1.6c-.245-.107-.423.064-.423.164v8.156c0 .253.338.194.45.133c2.901-1.643 8.748-4.95 8.926-5.033c.178-.081.326-.034.378 0l1.105.631c.187.185.048.34-.045.394l-11.862 6.65c-.396.223-.465-.031-.45-.187V5.243c.013-.225.22-.175.323-.12");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s-uxhdv6r {
  fill: var(--svg-color--2c5ff3, #2c5ff3);
  d: path("m19.675 18.878l-6.202-3.476l1.46-.82c.11-.06.25-.025.307 0l2.837 1.602c.245.106.423-.066.423-.165V7.863c0-.253-.338-.194-.449-.133c-2.901 1.643-8.749 4.95-8.927 5.032s-.326.034-.378 0l-1.105-.63c-.187-.186-.048-.34.045-.394l11.862-6.65c.396-.223.465.031.45.187v13.482c-.013.225-.22.174-.323.12");
}

</style>
