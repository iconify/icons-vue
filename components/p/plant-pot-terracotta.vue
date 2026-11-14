<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j59pirb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:plant-pot-terracotta" /></template>
<style>
.j59pirb5x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 10.25h5q2.5 0 2.5 2.5q0 1.036-.732 1.768q-.596.596-1.393.707q.334.713.154 1.549l-.75 3.5q-.423 1.976-2.444 1.976h-6.17q-2.021 0-2.444-1.976l-.75-3.5q-.18-.836.154-1.549q-.797-.111-1.393-.707q-.732-.732-.732-1.768q0-2.5 2.5-2.5h5V8.715q-2.075-.201-3.512-1.542Q6 5.551 6 3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014q3.772 0 5.189 2.653Q13.31 1.75 17.25 1.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141T18 2.5q0 2.613-1.601 4.379q-1.454 1.604-3.649 1.833zm.099-3.047q3.295-.383 3.616-3.905q-3.034.386-3.616 3.905m-1.713.004q-3.239-.345-3.593-3.414q2.992.344 3.593 3.414");
}

</style>
