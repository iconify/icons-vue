<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk9yft3ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-key-sharp" /></template>
<style>
.lk9yft3ai {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4C10.6569 4 12 5.3431 12 7C12 8.6569 10.6569 10 9 10C7.3432 10 6 8.6569 6 7C6 5.3431 7.3432 4 9 4ZM11 21L2 21L2 20C2 16.6863 4.6863 14 8 14L10 14C10.2868 14 10.5733 14.0206 10.8571 14.0615M18 19C18 20.1046 17.1046 21 16 21C14.8954 21 14 20.1046 14 19C14 17.8954 14.8954 17 16 17C17.1046 17 18 17.8954 18 19ZM17.4142 17.5858L21.5 13.5L21.7929 13.2071M20.4393 14.5607L22 16.1214L22.2929 16.4143");
}

</style>
