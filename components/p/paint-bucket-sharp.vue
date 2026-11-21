<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0xqvf4od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paint-bucket-sharp" /></template>
<style>
.j0xqvf4od {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 9C4 7.6193 7.5817 6.5 12 6.5C16.4183 6.5 20 7.6193 20 9C20 10.3807 16.4183 11.5 12 11.5C7.5817 11.5 4 10.3807 4 9ZM4 9L6 22L18 22L20 9M4 9C4.5368 4.9922 7.9564 2 12 2C16.0436 2 19.4632 4.9922 20 9M9 11.3176L9 17M14.5 11.3748L14.5 15");
}

</style>
