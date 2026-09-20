<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4iacgb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-2-outline-rounded" /></template>
<style>
.i4iacgb1v {
  fill: currentColor;
  d: path("M6.616 20q-.691 0-1.153-.462T5 18.384v-3q0-.213.143-.356q.144-.144.357-.144t.357.144q.143.143.143.356v3q0 .231.192.424t.423.192h10.77q.23 0 .423-.192t.192-.424v-3q0-.213.143-.356q.143-.144.357-.144t.357.144t.143.356v3q0 .691-.462 1.153T17.384 20zM3.5 12.5q-.213 0-.357-.143T3 12t.143-.357t.357-.143H5V5.616q0-.691.463-1.153T6.616 4h10.769q.69 0 1.153.463T19 5.616V11.5h1.5q.214 0 .357.143T21 12t-.143.357t-.357.143zm2.5-1h12V5.616q0-.231-.192-.424T17.384 5H6.616q-.231 0-.424.192T6 5.616zM18 19H6zm0-14H6z");
}

</style>
