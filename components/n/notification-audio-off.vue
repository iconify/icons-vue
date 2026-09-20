<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn7ounb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:notification-audio-off" /></template>
<style>
.nn7ounb-x {
  fill: currentColor;
  d: path("M16.442 12.616V7.385h.885v5.23zm-2.326-1.308V8.692H15v2.616zm4.653 0V8.692h.885v2.616zM5 18.769v-1h1.616V9.846q0-.592.125-1.16q.126-.566.378-1.105l2.266 2.265H7.969l-5.3-5.294l.708-.713l17.285 17.284l-.708.708l-3.068-3.062zm6.997 2.616q-.668 0-1.14-.475t-.472-1.14h3.23q0 .67-.475 1.142q-.476.472-1.143.472M11.92 9.5L8.316 5.894q.557-.521 1.238-.866T11 4.546V4q0-.417.291-.708q.291-.292.707-.292t.709.292T13 4v.546q.575.092 1.074.309q.498.216.949.504q-1.279.522-2.116 1.616T11.92 9.5");
}

</style>
