<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl009tz-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:terminal-2-outline-sharp" /></template>
<style>
.sl009tz-t {
  fill: currentColor;
  d: path("M12.5 19v-1h7v1zm-6.77-4l-.707-.688L9.329 10L5.023 5.689L5.731 5l5 5z");
}

</style>
