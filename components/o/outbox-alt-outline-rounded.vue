<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mizsz1-ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:outbox-alt-outline-rounded" /></template>
<style>
.mizsz1-ix {
  fill: currentColor;
  d: path("M16.2 12.9q.55-.275.55-.9t-.55-.9L7.45 6.725q-.5-.25-.975.038T6 7.625v8.75q0 .575.475.863t.975.037zM8 15v-2l3-1l-3-1V9l6.5 3zm-3 6q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
