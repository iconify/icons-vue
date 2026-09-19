<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u95wjvjtv"/><path class="v21tfjb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vepatria" /></template>
<style>
.u95wjvjtv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.048 40.341l3.057-24.103c.624-4.92 6.223-9.812 11.182-9.812h11.116c4.016 0 9.063 4.54 8.52 8.52L39.22 27.417c-.639 4.675-6.413 8.745-11.13 8.745H17.56c-4.729 0-8.16 4.182-8.765 4.852c-1.064 1.184-1.865.262-1.746-.674");
}

.v21tfjb_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.984 34.701c7.504-5.417 16.705-12.17 31.22-8.338m-1.507-11.47q1.435.24 2.835.63M9.626 20.774c4.723-2.409 9.801-4.358 14.898-5.42m7.161 3.997l-2.898 1.808l.014-3.6l-2.836-2.296l3.441-.63l1.132-3.389l2.04 3.208l3.777.315l-2.332 2.69l1.243 3.547z");
}

</style>
