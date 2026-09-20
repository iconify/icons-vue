<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgukc-yil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-remote-comfort-sensor-rounded" /></template>
<style>
.kgukc-yil {
  fill: currentColor;
  d: path("M9.983 17.594q-.83-.829-.83-2.017t.83-2.018q.829-.828 2.017-.828t2.017.828t.83 2.018t-.83 2.017q-.828.829-2.017.829t-2.017-.829M12 5.731q-1.889 0-3.605.679t-3.07 1.88q-.177.14-.371.15t-.365-.15q-.166-.16-.156-.363q.01-.204.18-.344q1.47-1.304 3.33-2.078Q9.801 4.73 12 4.73t4.058.774q1.86.774 3.329 2.083q.17.14.178.342t-.16.36q-.17.16-.362.15t-.368-.15q-1.354-1.201-3.07-1.88q-1.716-.68-3.605-.68m0 4q-1.102 0-2.037.337t-1.77 1.025q-.178.135-.382.142q-.203.007-.375-.159q-.146-.14-.146-.338t.171-.333q1.025-.835 2.134-1.254T12 8.73t2.402.42t2.13 1.254q.172.135.175.333t-.143.338q-.166.166-.37.159t-.38-.142q-.835-.688-1.774-1.025q-.938-.336-2.04-.336");
}

</style>
