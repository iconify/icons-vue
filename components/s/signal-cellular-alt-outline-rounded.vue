<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a31-cqkjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-alt-outline-rounded" /></template>
<style>
.a31-cqkjs {
  fill: currentColor;
  d: path("M5.438 19.563Q5 19.125 5 18.5v-3q0-.625.438-1.062T6.5 14t1.063.438T8 15.5v3q0 .625-.437 1.063T6.5 20t-1.062-.437m6 0Q11 19.125 11 18.5v-8q0-.625.438-1.062T12.5 9t1.063.438T14 10.5v8q0 .625-.437 1.063T12.5 20t-1.062-.437m6 0Q17 19.125 17 18.5v-13q0-.625.438-1.062T18.5 4t1.063.438T20 5.5v13q0 .625-.437 1.063T18.5 20t-1.062-.437");
}

</style>
