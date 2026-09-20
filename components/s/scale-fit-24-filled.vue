<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnk8k0clt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scale-fit-24-filled" /></template>
<style>
.rnk8k0clt {
  fill: currentColor;
  d: path("M4.25 4A2.25 2.25 0 0 0 2 6.25v11.5A2.25 2.25 0 0 0 4.25 20h15.5A2.25 2.25 0 0 0 22 17.75V6.25A2.25 2.25 0 0 0 19.75 4zm3.744 5.436a.75.75 0 0 1 .07 1.058l-.661.756h2.862a.75.75 0 0 1 0 1.5H7.403l.661.756a.75.75 0 0 1-1.128.988l-1.75-2a.75.75 0 0 1 0-.988l1.75-2a.75.75 0 0 1 1.058-.07m7.956 1.058a.75.75 0 0 1 1.13-.988l1.75 2a.75.75 0 0 1 0 .988l-1.75 2a.75.75 0 0 1-1.13-.988l.662-.756H13.75a.75.75 0 0 1 0-1.5h2.862z");
}

</style>
