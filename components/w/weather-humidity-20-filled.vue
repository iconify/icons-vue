<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tlsdocflo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-humidity-20-filled" /></template>
<style>
.tlsdocflo {
  fill: currentColor;
  d: path("M12 17a.5.5 0 0 1 0 1H8a.5.5 0 0 1 0-1zm2.099-2a.5.5 0 0 1 0 1h-8.2a.5.5 0 0 1 0-1zm.75-2a.5.5 0 0 1 0 1h-9.7a.5.5 0 0 1 0-1zM15 11a.5.5 0 0 1 0 1H5a.5.5 0 0 1 0-1zM9.648 2.147a.5.5 0 0 1 .707 0c.532.531 1.805 2.063 2.947 3.902c.75 1.208 1.472 2.598 1.874 3.951H4.828c.402-1.353 1.124-2.743 1.874-3.951c1.142-1.84 2.415-3.37 2.946-3.902");
}

</style>
