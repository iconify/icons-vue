<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c6c0h142l"/><path class="gzc0_wbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobi" /></template>
<style>
.c6c0h142l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.417 32.062c6.305-6.305 6.305-16.528 0-22.833c-6.306-6.305-16.528-6.305-22.833 0c-6.306 6.305-6.306 16.528 0 22.833L24.022 43.5z");
}

.gzc0_wbad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.634 28.934c1.344 0 2.443 1.1 2.443 2.444s-1.1 2.443-2.443 2.443h-4.032v-9.774h4.032c1.344 0 2.443 1.1 2.443 2.444s-1.1 2.443-2.443 2.443m.056 0H19m9.961-5.146v9.774M13.965 21.586l.047-9.42l4.947 9.49l4.817-9.502l-.013 9.574M35.52 16.67a4.689 4.689 0 1 0-9.377 0v.397a4.689 4.689 0 1 0 9.378 0z");
}

</style>
