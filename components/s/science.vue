<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqp6-3bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:science" /></template>
<style>
.gqp6-3bld {
  fill: currentColor;
  d: path("M5 21q-1.275 0-1.812-1.137t.262-2.113L9 11V5H8q-.425 0-.712-.288T7 4t.288-.712T8 3h8q.425 0 .713.288T17 4t-.288.713T16 5h-1v6l5.55 6.75q.8.975.263 2.113T19 21z");
}

</style>
