<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejz_dlbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:medication-liquid-outline" /></template>
<style>
.ejz_dlbxj {
  fill: currentColor;
  d: path("M4 5.23v-1h10v1zm3.885 11.886h2.23v-2.5h2.5v-2.231h-2.5v-2.5h-2.23v2.5h-2.5v2.23h2.5zM4.615 20q-.69 0-1.153-.462T3 18.384V8.616q0-.691.463-1.153T4.615 7h8.77q.69 0 1.152.463T15 8.616v9.769q0 .69-.462 1.153T13.385 20zm0-1h8.77q.23 0 .423-.192t.192-.424V8.616q0-.231-.192-.424T13.385 8h-8.77q-.23 0-.423.192T4 8.616v9.769q0 .23.192.423t.423.192m14.154-5.077q-.875-.425-1.437-1.326q-.563-.9-.563-2.089q0-1.496.728-2.502T19.269 7t1.772 1.006t.728 2.494q0 1.196-.562 2.097t-1.438 1.326V19.5q0 .213-.144.356T19.27 20t-.356-.144t-.144-.356zm1.477-1.595q.523-.671.523-1.828q0-1.156-.526-1.828T19.266 8q-.45 0-.974.672q-.523.671-.523 1.828q0 1.156.526 1.828t.977.672t.974-.672M19.27 10.5");
}

</style>
