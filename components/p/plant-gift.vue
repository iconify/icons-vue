<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cif9zsron"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:plant-gift" /></template>
<style>
.cif9zsron {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 22.25H8.625q-3.375 0-3.375-3.375v-1.25q0-1.074.584-1.906q-.771-.121-1.352-.701q-.732-.732-.732-1.768q0-2.5 2.5-2.5h5V8.715q-2.075-.201-3.512-1.542Q6 5.551 6 3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014q3.772 0 5.189 2.653Q13.31 1.75 17.25 1.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T18 2.5q0 2.613-1.601 4.379q-1.454 1.604-3.649 1.833v2.038h5q2.5 0 2.5 2.5q0 1.036-.732 1.768q-.514.513-1.177.667q.409.766.409 1.94v1.25q0 3.375-3.375 3.375zm.849-15.047q3.295-.383 3.616-3.905q-3.034.386-3.616 3.905m-1.713.004q-3.239-.345-3.593-3.414q2.992.344 3.593 3.414");
}

</style>
