<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d--mtz5wl"/><path class="d-vmnac4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:splayer" /></template>
<style>
.d--mtz5wl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.825 22.043L13.435 6.806c-1.507-.87-3.39.218-3.39 1.958v30.472c0 1.74 1.883 2.828 3.39 1.958l26.39-15.237c1.507-.87 1.507-3.045 0-3.915Z");
}

.d-vmnac4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.305 10.772c-2.533 6.914 3.665 7.581 6.624 8.743c4.694 1.842 7.516 4.712 6.65 10.048M10.045 17.245c.865 4.86 4.016 7.883 7.833 8.757c3.498.801 7.476 4.379 3.224 10.766");
}

</style>
