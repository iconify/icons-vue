<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="cyrkqqbha"/><path class="bc-3lbf8u"/><path class="b65nw1jja"/><path class="a3cw94v-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:nazar-amulet" /></template>
<style>
.a3cw94v-a {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M23.075 17.825c0 2.665-2.235 4.908-4.9 4.908s-4.732-2.243-4.732-4.908s2.067-4.835 4.732-4.835s4.9 2.17 4.9 4.835");
}

.b65nw1jja {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M25.871 18c0 4.418-3.453 8.112-7.871 8.112S10.261 22.418 10.261 18s3.321-7.785 7.739-7.785s7.871 3.367 7.871 7.785");
}

.bc-3lbf8u {
  fill: var(--svg-color--fff, #fff);
  d: path("M29.994 18c0 3.314-1.092 6.559-3.264 8.73s-5.417 2.798-8.73 2.798s-6.089-1.096-8.261-3.267S6.312 21.314 6.312 18s.9-6.445 3.071-8.617S14.686 5.608 18 5.608s6.203 1.846 8.375 4.017s3.619 5.061 3.619 8.375");
}

.cyrkqqbha {
  fill: var(--svg-color--1213bd, #1213bd);
  d: path("M36 18.302c0 4.981-2.46 9.198-5.655 12.462s-7.323 5.152-12.199 5.152s-9.764-1.112-12.959-4.376S0 23.283 0 18.302s2.574-9.38 5.769-12.644S13.271 0 18.146 0s9.394 2.178 12.589 5.442S36 13.322 36 18.302");
}

</style>
