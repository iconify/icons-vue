<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db19ynbqi"/><path class="kmo065zza"/><path class="uv20i7b6z"/><path class="lwypf-boe"/><path class="pirwrdbar"/><path class="o8bcbj09y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-bold" /></template>
<style>
.db19ynbqi {
  fill: currentColor;
  d: path("M16.959 9.75C16.5448 9.75 16.209 9.41421 16.209 9L16.209 2C16.209 1.58579 16.5448 1.25 16.959 1.25C17.3732 1.25 17.709 1.58579 17.709 2L17.709 9C17.709 9.41421 17.3732 9.75 16.959 9.75Z");
}

.kmo065zza {
  fill: currentColor;
  d: path("M7 12.5C5.34315 12.5 4 11.1569 4 9.5C4 7.84315 5.34315 6.5 7 6.5C8.65685 6.5 10 7.84315 10 9.5C10 11.1569 8.65685 12.5 7 12.5Z");
}

.lwypf-boe {
  fill: currentColor;
  d: path("M6.20901 15C6.20901 14.5858 6.5448 14.25 6.95901 14.25C7.37322 14.25 7.70901 14.5858 7.70901 15V22C7.70901 22.4142 7.37322 22.75 6.95901 22.75C6.5448 22.75 6.20901 22.4142 6.20901 22V15Z");
}

.o8bcbj09y {
  fill: currentColor;
  d: path("M6.20901 2C6.20901 1.58579 6.5448 1.25 6.95901 1.25C7.37322 1.25 7.70901 1.58579 7.70901 2V4C7.70901 4.41421 7.37322 4.75 6.95901 4.75C6.5448 4.75 6.20901 4.41421 6.20901 4V2Z");
}

.pirwrdbar {
  fill: currentColor;
  d: path("M16.959 22.75C16.5448 22.75 16.209 22.4142 16.209 22V20C16.209 19.5858 16.5448 19.25 16.959 19.25C17.3732 19.25 17.709 19.5858 17.709 20V22C17.709 22.4142 17.3732 22.75 16.959 22.75Z");
}

.uv20i7b6z {
  fill: currentColor;
  d: path("M17 11.5C15.3431 11.5 14 12.8431 14 14.5C14 16.1569 15.3431 17.5 17 17.5C18.6569 17.5 20 16.1569 20 14.5C20 12.8431 18.6569 11.5 17 11.5Z");
}

</style>
