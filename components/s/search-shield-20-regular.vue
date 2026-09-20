<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x7tm32bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-shield-20-regular" /></template>
<style>
.x7tm32bzm {
  fill: currentColor;
  d: path("M5.12 10.036a.574.574 0 0 1 .76 0c.509.484 1.484 1.254 2.683 1.412c.24.032.437.212.437.438v2.111c0 2.838-2.784 3.869-3.386 4.059a.37.37 0 0 1-.227 0C4.785 17.866 2 16.836 2 13.997v-2.111c0-.226.197-.406.437-.438c1.199-.158 2.174-.928 2.682-1.412M9.5 3a6.5 6.5 0 0 1 4.937 10.73l3.417 3.416a.5.5 0 0 1-.638.765l-.07-.058l-3.417-3.417a6.47 6.47 0 0 1-4.156 1.562c.142-.31.255-.647.33-1.015a5.47 5.47 0 0 0 3.824-1.963A5.5 5.5 0 1 0 4 9.5q0 .088.004.175c-.274.212-.6.422-.96.574A6.5 6.5 0 0 1 9.5 3");
}

</style>
