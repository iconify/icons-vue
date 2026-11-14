<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="retpnql4d"/><path class="hi05hw3ig"/><path class="vkbd1mnmv"/><path class="ntvh8f-mn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sprout-linear" /></template>
<style>
.hi05hw3ig {
  d: path("M11.9678 15.269C8.16782 15.269 4.16782 12.669 3.56782 9.46898C3.16782 7.26898 5.16782 6.26898 7.56782 6.96898C10.3678 7.76898 11.9678 10.869 11.9678 15.269Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ntvh8f-mn {
  d: path("M6.46777 21.669C9.46777 20.269 14.4678 20.269 17.4678 21.669");
}

.retpnql4d {
  d: path("M11.9678 20.669V10.869");
}

.vkbd1mnmv {
  d: path("M11.9678 10.869C11.9678 6.46903 13.7678 3.26902 16.7678 2.46902C19.1678 1.86902 20.9678 3.26902 20.3678 5.66902C19.5678 8.86902 15.7678 10.869 11.9678 10.869Z");
}

</style>
