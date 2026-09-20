<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x86jt_bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:synagogue-sharp" /></template>
<style>
.x86jt_bsq {
  fill: currentColor;
  d: path("M19 8V7q0-.825.588-1.412T21 5t1.413.588T23 7v1zM1 8V7q0-.825.588-1.412T3 5t1.413.588T5 7v1zm0 13V9h4v12zm5 0V8l6-5l6 5v13h-4v-7h-4v7zm13 0V9h4v12zm-5.937-9.937q.437-.438.437-1.063t-.437-1.062T12 8.5t-1.062.438T10.5 10t.438 1.063T12 11.5t1.063-.437");
}

</style>
