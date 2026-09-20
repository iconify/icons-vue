<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szs1tjbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-heart-outline-rounded" /></template>
<style>
.szs1tjbft {
  fill: currentColor;
  d: path("M6.33 14.973q1.359-.64 2.709-.98t2.711-.377q.004.096.002.18t.06.166q.117.061.204.157t.059.233t-.141.203t-.25.06q-1.253.022-2.485.342t-2.391.893q-.38.202-.593.494Q6 16.637 6 16.97v.647h6.958q.25 0 .375.155t.125.341t-.125.345t-.375.159h-6.92q-.44 0-.739-.3T5 17.577v-.608q0-.619.36-1.158q.361-.54.97-.838m3.547-4.465Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877m3.535-.711Q14 9.21 14 8.385t-.588-1.413T12 6.385t-1.413.587T10 8.385t.587 1.412t1.413.588t1.412-.588m4.123 3.903q.442-.442.79-.725t.961-.283q.781 0 1.248.532T21 14.436q0 .319-.121.638q-.121.318-.379.576l-2.4 2.4q-.242.242-.565.242t-.566-.242l-2.396-2.396q-.286-.287-.395-.597q-.109-.312-.109-.623q0-.68.484-1.21t1.24-.532q.6 0 .944.277t.798.731");
}

</style>
