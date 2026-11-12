<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzlk0ybdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smart-meter-fill" /></template>
<style>
.qzlk0ybdi {
  fill: currentColor;
  d: path("M15 3a1 1 0 0 1 2 0h2a3 3 0 0 1 3 3v13a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h2a1 1 0 0 1 2 0ZM7 7v3a1 1 0 0 0 2 0V7a1 1 0 0 0-2 0m4 0v3a1 1 0 0 0 2 0V7a1 1 0 0 0-2 0m4 0v3a1 1 0 0 0 2 0V7a1 1 0 0 0-2 0m-5.081 7.296c-.656.206-1.298.544-1.719 1.104a1 1 0 0 0 .2 1.4a1 1 0 0 0 1.4-.2c.145-.193.499-.327.718-.396A5 5 0 0 1 12 16c.5 0 1.004.054 1.482.204c.172.054.342.121.497.215a.8.8 0 0 1 .221.181a1 1 0 0 0 1.6-1.2c-.421-.56-1.063-.898-1.719-1.104c-1.272-.399-2.89-.399-4.162 0M12 17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
