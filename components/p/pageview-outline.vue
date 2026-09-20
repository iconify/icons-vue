<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0glkyr4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pageview-outline" /></template>
<style>
.k0glkyr4o {
  fill: currentColor;
  d: path("M15.712 19H4.616q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19h-.823l-4.816-4.815q-.467.407-1.031.611Q12.15 15 11.5 15q-1.452 0-2.476-1.024T8 11.5t1.024-2.476T11.5 8t2.476 1.024T15 11.5q0 .54-.117.987t-.467.951L18.977 18h.408q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192h10.096zm-2.437-5.725Q14 12.55 14 11.5t-.725-1.775T11.5 9t-1.775.725T9 11.5t.725 1.775T11.5 14t1.775-.725M4 18V6z");
}

</style>
