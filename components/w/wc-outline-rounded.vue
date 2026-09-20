<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnu13nb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wc-outline-rounded" /></template>
<style>
.vnu13nb_e {
  fill: currentColor;
  d: path("M6.154 20.692V14.5h-.692q-.348 0-.578-.23t-.23-.578V9q0-.633.434-1.066Q5.52 7.5 6.154 7.5h2.692q.633 0 1.067.434q.433.433.433 1.066v4.692q0 .349-.23.578q-.23.23-.577.23h-.693v6.192q0 .349-.23.578q-.23.23-.577.23H6.962q-.348 0-.578-.23t-.23-.578M6.299 5.97q-.491-.491-.491-1.2q0-.71.491-1.202q.492-.491 1.201-.491t1.201.491q.491.491.491 1.201T8.701 5.97T7.5 6.462T6.299 5.97M15.5 20.692V16h-1.375q-.385 0-.637-.316q-.251-.317-.134-.701l1.735-6.48q.142-.476.525-.74q.384-.263.886-.263t.886.264t.526.74l1.734 6.479q.118.384-.134.7q-.252.317-.637.317H17.5v4.692q0 .349-.23.578t-.578.23h-.384q-.348 0-.578-.23t-.23-.578M15.299 5.97q-.491-.491-.491-1.2q0-.71.491-1.202q.492-.491 1.201-.491t1.201.491q.491.491.491 1.201t-.491 1.201t-1.201.492t-1.201-.492");
}

</style>
