<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljmxxz7il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:soap-sharp" /></template>
<style>
.ljmxxz7il {
  fill: currentColor;
  d: path("M19 22H2V10.975l9.625-6.25L13.25 6.35L11.3 9.5H20v2h-8V13h10v2H12v1.5h9v2h-9V20h7zM14.513 7.488Q14 6.975 14 6.25t.513-1.237T15.75 4.5t1.238.513t.512 1.237t-.513 1.238T15.75 8t-1.237-.513m1.924-3.925Q16 3.125 16 2.5t.438-1.062T17.5 1t1.063.438T19 2.5t-.437 1.063T17.5 4t-1.062-.437m3.15 3.85Q19 6.825 19 6t.588-1.412T21 4t1.413.588T23 6t-.587 1.413T21 8t-1.412-.587");
}

</style>
