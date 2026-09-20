<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr1y8hbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:x-circle-rounded" /></template>
<style>
.rr1y8hbao {
  fill: currentColor;
  d: path("m11.989 12.496l2.494 4.096q.129.197.297.212t.322-.083t.206-.263t-.077-.362L12.552 11.8l2.467-3.946q.123-.171.074-.334t-.203-.241t-.312-.063t-.282.192l-2.283 3.738L9.75 7.408q-.129-.197-.294-.212t-.325.083t-.209.254q-.049.155.08.351l2.454 3.922l-2.717 4.34q-.123.171-.074.334t.202.241t.313.06q.159-.017.282-.189zM8.494 20.3q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701");
}

</style>
