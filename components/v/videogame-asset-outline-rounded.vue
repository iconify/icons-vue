<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h82lneyyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videogame-asset-outline-rounded" /></template>
<style>
.h82lneyyh {
  fill: currentColor;
  d: path("M4.616 17q-.691 0-1.153-.462T3 15.385v-6.77q0-.69.463-1.152T4.615 7h14.77q.69 0 1.152.463T21 8.616v6.769q0 .69-.463 1.153T19.385 17zm0-1h14.769q.23 0 .423-.192t.192-.423v-6.77q0-.23-.192-.423T19.385 8H4.615q-.23 0-.423.192T4 8.616v6.769q0 .23.192.423t.423.192M7.5 12.5V14q0 .214.143.357T8 14.5t.357-.143T8.5 14v-1.5H10q.214 0 .357-.143T10.5 12t-.143-.357T10 11.5H8.5V10q0-.213-.143-.357T8 9.5t-.357.143T7.5 10v1.5H6q-.213 0-.357.143T5.5 12t.143.357T6 12.5zm7.707 1.707q.293-.294.293-.707t-.293-.707t-.707-.293t-.707.293t-.293.707t.293.707t.707.293t.707-.293m3-3q.293-.293.293-.707t-.293-.707T17.5 9.5t-.707.293t-.293.707t.293.707t.707.293t.707-.293M4 16V8z");
}

</style>
