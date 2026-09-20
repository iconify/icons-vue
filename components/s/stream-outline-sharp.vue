<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfgdz9boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stream-outline-sharp" /></template>
<style>
.sfgdz9boe {
  fill: currentColor;
  d: path("M2.934 13.066Q2.5 12.633 2.5 12t.434-1.066T4 10.5t1.066.434Q5.5 11.367 5.5 12t-.434 1.066T4 13.5t-1.066-.434m2.716 5.942l-.708-.708L8.6 14.642l.708.708zm3-9.7L4.992 5.65l.708-.708L9.358 8.6zm2.284 11.758Q10.5 20.633 10.5 20t.434-1.066T12 18.5t1.066.434q.434.433.434 1.066t-.434 1.066q-.433.434-1.066.434t-1.066-.434m0-16Q10.5 4.633 10.5 4t.434-1.066T12 2.5t1.066.434T13.5 4t-.434 1.066T12 5.5t-1.066-.434M15.35 9.32l-.708-.719l3.708-3.658l.708.708zm3 9.689l-3.658-3.658l.708-.708l3.658 3.658zm.584-5.942Q18.5 12.633 18.5 12t.434-1.066T20 10.5t1.066.434q.434.433.434 1.066t-.434 1.066T20 13.5t-1.066-.434");
}

</style>
