<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf77zuv3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stock-media-rounded" /></template>
<style>
.tf77zuv3w {
  fill: currentColor;
  d: path("M4.616 14q-.691 0-1.153-.462T3 12.385v-7.77q0-.69.463-1.153T4.615 3h7.77q.69 0 1.152.463T14 4.615v7.77q0 .69-.462 1.152T12.385 14zM8 11.75l-1.038-1.433q-.056-.08-.162-.08t-.161.08l-1.012 1.36q-.08.106-.025.214q.056.109.186.109h5.423q.131 0 .187-.109q.056-.108-.025-.214L9.862 9.711q-.056-.08-.162-.08t-.161.08zm6.73 8.52Q14 19.537 14 18.5t.73-1.77T16.5 16q.448 0 .82.146t.68.413v-4.751q0-.348.23-.578t.578-.23H20.5q.214 0 .357.143T21 11.5t-.143.357T20.5 12H19v6.5q0 1.039-.73 1.77T16.5 21t-1.77-.73");
}

</style>
