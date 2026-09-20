<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g02-4d2rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-camera-back-outline" /></template>
<style>
.g02-4d2rs {
  fill: currentColor;
  d: path("M7.5 16.616h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zM4.616 20q-.691 0-1.153-.462T3 18.384V7.616q0-.691.463-1.153T4.615 6h2.958l1.85-2h5.154l1.85 2h2.958q.69 0 1.152.463T21 7.616v10.769q0 .69-.463 1.153T19.385 20zm0-1h14.769q.269 0 .442-.173t.173-.442V7.615q0-.269-.173-.442T19.385 7h-3.397l-1.844-2H9.856L8.012 7H4.615q-.269 0-.442.173T4 7.616v10.769q0 .269.173.442t.443.173M12 13");
}

</style>
