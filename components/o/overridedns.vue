<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kuxkcobzu"/><path class="w_4emfz_x"/><path class="lp_j3ygky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:overridedns" /></template>
<style>
.kuxkcobzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.914 14.296L23.947 4.5L7.086 14.235l16.967 9.796z");
}

.lp_j3ygky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.373 32.589V21.516l6.393 14.764V25.207m10.712 9.719c.592.542 1.334.443 2.366-.153l1.429-.825a5.31 5.31 0 0 0 2.407-4.158c0-1.529-1.078-2.146-2.407-1.378l-1.579.91c-1.33.769-2.407.151-2.407-1.377a5.31 5.31 0 0 1 2.407-4.159l1.429-.825c1.032-.596 1.774-.695 2.366-.152");
}

.w_4emfz_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.053 24.031L7.086 14.235v19.469L24.053 43.5zm16.861-9.735l-16.861 9.735V43.5l16.861-9.735zM15.885 15.62l9.59-5.536l2.17 1.254c2.332 1.346 2.344 3.522.027 4.86l-1.199.692a9.3 9.3 0 0 1-8.417-.016Z");
}

</style>
