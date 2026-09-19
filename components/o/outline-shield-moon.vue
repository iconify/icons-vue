<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wztibb18j"/><path class="xii8v8beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-shield-moon" /></template>
<style>
.wztibb18j {
  fill: currentColor;
  d: path("M12 2L4 5v6.09c0 5.05 3.41 9.76 8 10.91c4.59-1.15 8-5.86 8-10.91V5zm6 9.09c0 4-2.55 7.7-6 8.83c-3.45-1.13-6-4.82-6-8.83v-4.7l6-2.25l6 2.25z");
}

.xii8v8beu {
  fill: currentColor;
  d: path("M9.01 14.33c1.75 2.17 5.12 2.24 6.96.07c.23-.27.08-.68-.26-.74a4.5 4.5 0 0 1-3.18-2.2a4.5 4.5 0 0 1-.32-3.86a.453.453 0 0 0-.51-.6c-3.34.62-4.89 4.61-2.69 7.33");
}

</style>
