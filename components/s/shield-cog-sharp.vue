<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm8x4bc6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-cog-sharp" /></template>
<style>
.mm8x4bc6e {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.99 12H17M14.114 14.114L15.535 15.535M12 14.99V17M9.886 14.114L8.465 15.535M9.01 12H7M9.886 9.886L8.465 8.464M12 9.01V7M14.114 9.886L15.535 8.464M20 5.309V15.778L18.612 17.573C17.41 19.128 15.503 20.87 12.83 21.852C12.294 22.049 11.706 22.049 11.17 21.852C8.497 20.87 6.59 19.128 5.388 17.573L4 15.778V5.309L5.182 5.168C7.83 4.854 9.83 3.532 11.024 2.373C11.537 1.876 12.463 1.876 12.976 2.373C14.17 3.532 16.17 4.854 18.817 5.168L20 5.309ZM14.667 12C14.667 13.473 13.473 14.667 12 14.667C10.527 14.667 9.333 13.473 9.333 12C9.333 10.527 10.527 9.333 12 9.333C13.473 9.333 14.667 10.527 14.667 12Z");
}

</style>
