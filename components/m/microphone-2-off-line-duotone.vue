<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsrhfac5n"/><path class="rst3o_bug"/><path class="j-r-_cchv"/><path class="lhp1e8ukj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-2-off-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-r-_cchv {
  d: path("M16.9995 10.4561V11.0001C16.9995 13.7615 14.7609 16.0001 11.9995 16.0001C11.8075 16.0001 11.6175 15.9891 11.4785 15.9771");
}

.lhp1e8ukj {
  d: path("M4 10V11C4 13.464 5.114 15.667 6.865 17.135M8.986 18.413C9.916 18.792 10.933 19 12 19M12 19C16.418 19 20 15.418 20 11V10M12 19V22M13.5 8H16M7 8H9M7 11H9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.rst3o_bug {
  d: path("M9 15C7.785 14.088 7 12.636 7 11V8C7 5.2386 9.2386 3 12 3C14.448 3 16.486 4.76 16.916 7.084");
}

</style>
