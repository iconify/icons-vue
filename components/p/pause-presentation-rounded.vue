<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq_tbwb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pause-presentation-rounded" /></template>
<style>
.uq_tbwb0v {
  fill: currentColor;
  d: path("M10.665 15.357q.143-.143.143-.357V9q0-.213-.143-.357t-.357-.143t-.357.143T9.808 9v6q0 .214.143.357t.357.143t.357-.143m3.384 0q.143-.143.143-.357V9q0-.213-.143-.357t-.357-.143t-.356.143t-.144.357v6q0 .214.144.357t.356.143t.357-.143M4.616 19q-.691 0-1.154-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
