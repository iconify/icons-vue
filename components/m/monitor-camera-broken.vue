<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uz-6ybbfc"/><path class="p0mqq1_8c"/><path class="kva043bzk"/><path class="jt_thrbns"/><path class="kuvu9bc5l"/><path class="rainf0t7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-camera-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jt_thrbns {
  d: path("M12 17L12 22");
}

.kuvu9bc5l {
  d: path("M22 10V11C22 13.8284 22 15.2426 21.1213 16.1213C20.2426 17 18.8284 17 16 17H8C5.17157 17 3.75736 17 2.87868 16.1213C2 15.2426 2 13.8284 2 11V10M9.5 2C6.21252 2 4.56878 2 3.46243 2.90796C3.25989 3.07418 3.07418 3.25989 2.90796 3.46243C2.40259 4.07821 2.17851 4.86048 2.07915 6");
}

.kva043bzk {
  d: path("M16 22H8");
}

.p0mqq1_8c {
  d: path("M19 3.75003L20.6154 3.07695C21.2416 2.81603 21.5547 2.68557 21.7774 2.834C22 2.98243 22 3.32163 22 4.00003V6.00003C22 6.67842 22 7.01762 21.7774 7.16605C21.5547 7.31448 21.2416 7.18402 20.6154 6.9231L19 6.25003V3.75003Z");
}

.rainf0t7w {
  d: path("M12 13H2M22 13H16");
}

.uz-6ybbfc {
  d: path("M15 8H16C17.4142 8 18.1213 8 18.5607 7.56066C19 7.12132 19 6.41421 19 5C19 3.58579 19 2.87868 18.5607 2.43934C18.1213 2 17.4142 2 16 2H15C13.5858 2 12.8787 2 12.4393 2.43934C12 2.87868 12 3.58579 12 5C12 6.41421 12 7.12132 12.4393 7.56066C12.8787 8 13.5858 8 15 8Z");
}

</style>
