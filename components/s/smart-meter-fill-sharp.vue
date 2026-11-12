<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh7qw2b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smart-meter-fill-sharp" /></template>
<style>
.yh7qw2b-r {
  fill: currentColor;
  d: path("M15 3a1 1 0 0 1 2 0h4a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h4a1 1 0 0 1 2 0ZM7 6v5h2V6Zm6 0h-2v5h2Zm2 0v5h2V6Zm-5.081 8.296c-.656.206-1.298.544-1.719 1.104a1 1 0 0 0 .2 1.4a1 1 0 0 0 1.4-.2c.145-.193.499-.327.718-.396A5 5 0 0 1 12 16c.5 0 1.004.054 1.482.204c.172.054.342.121.497.215a.8.8 0 0 1 .221.181a1 1 0 0 0 1.6-1.2c-.421-.56-1.063-.898-1.719-1.104c-1.272-.399-2.89-.399-4.162 0M12 17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
