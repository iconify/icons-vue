<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5cm8fb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wxt" /></template>
<style>
.c5cm8fb3n {
  fill: var(--svg-color--c9ffc6, #c9ffc6);
  d: path("m18.573 6.79l-1.99 7.104l-1.941-7.105h-3.425l-1.914 7.105L7.3 6.79H4.874l.668 2.368H3v1.895h3.092l.454 1.421H3v1.895h4.106l.814 2.842h2.897l2.129-8.053l2.105 8.053h2.898L21 6.79z");
}

</style>
