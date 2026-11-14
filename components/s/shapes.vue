<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o04om4jaq"/><path class="h9tn5_wer"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shapes" /></template>
<style>
.h9tn5_wer {
  d: path("M10.5 10.5H21V21H10.5Z");
}

.o04om4jaq {
  d: path("M13.939 7.684q-.036-.242-.094-.48q-.057-.238-.136-.469q-.078-.232-.177-.455q-.099-.224-.217-.438t-.255-.417t-.291-.393t-.324-.365t-.356-.335t-.384-.302t-.409-.267t-.432-.229t-.45-.19t-.465-.15t-.477-.107q-.24-.044-.484-.065Q8.745 3 8.5 3q-.135 0-.27.007q-.135.006-.269.019q-.134.014-.268.034q-.134.019-.266.046q-.132.026-.263.059t-.261.072t-.256.085q-.127.045-.252.097q-.124.051-.247.109q-.122.058-.241.121q-.119.064-.235.133q-.115.07-.228.145q-.112.075-.22.155q-.109.081-.213.166q-.105.086-.205.177q-.1.09-.195.186q-.096.095-.186.195q-.091.1-.177.205t-.166.213t-.155.22q-.075.113-.145.228q-.069.116-.133.235q-.063.119-.121.241q-.058.123-.109.247q-.052.125-.097.252t-.085.256t-.072.261t-.059.263t-.046.266t-.034.268q-.013.134-.019.269Q3 8.365 3 8.5q0 .246.022.491t.066.487q.043.241.108.479q.065.237.151.467t.193.452q.106.222.231.433q.126.211.27.411t.305.385t.338.356t.369.325t.396.29t.42.254t.442.215q.225.098.459.176q.233.077.472.133q.24.056.483.091");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
