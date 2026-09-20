<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":254};
const content = `<defs><linearGradient id="SVGqFpXpeGU" x1="50%" x2="50%" y1="-1.02%" y2="100%"><stop offset="0%" class="olsf03bjv"/><stop offset="100%" class="ypshk4bag"/></linearGradient></defs><path fill="url(#SVGqFpXpeGU)" class="xp2iihvxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:vaddy" /></template>
<style>
.olsf03bjv {
  stop-color: var(--svg-color--8fc53b, #8fc53b);
}

.xp2iihvxi {
  d: path("M189.574 13.209c25.131 18.66 41.421 48.556 41.421 82.263c0 56.554-45.846 102.4-102.4 102.4s-102.4-45.846-102.4-102.4c0-35.134 17.702-66.125 44.665-84.569C28.858 31.899 0 75.287 0 125.437c0 70.693 57.308 128.001 128 128.001s128-57.308 128-128.001c0-48.369-26.837-90.461-66.426-112.228M81.75 179.819c-18.812-13.967-31.006-36.346-31.006-61.576c0-42.333 34.318-76.65 76.651-76.65s76.65 34.317 76.65 76.65c0 26.299-13.251 49.497-33.433 63.302c31.439-15.716 53.041-48.193 53.041-85.733C223.653 42.897 180.756 0 127.84 0S32.028 42.897 32.028 95.812c0 36.207 20.088 67.714 49.722 84.007m78.2-80.775c0 17.645-14.304 31.95-31.95 31.95s-31.95-14.305-31.95-31.95c0-17.646 14.304-31.951 31.95-31.951s31.95 14.305 31.95 31.951");
}

.ypshk4bag {
  stop-color: var(--svg-color--48a23c, #48a23c);
}

</style>
