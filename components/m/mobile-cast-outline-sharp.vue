<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ophyxs8-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-cast-outline-sharp" /></template>
<style>
.ophyxs8-x {
  fill: currentColor;
  d: path("M6 22v-1.384q.571 0 .978.406t.407.978zm3.77 0q0-1.573-1.099-2.671T6 18.23v-1q1.987 0 3.378 1.39T10.77 22zm3.384 0q0-2.984-2.085-5.07Q8.984 14.847 6 14.847v-1q1.692 0 3.18.642t2.589 1.743t1.743 2.589t.642 3.18zm4.923-20v4.83H19v3.686h-.923V22h-1V3H7v8.462H6V2zm-5.49 4.086q.22-.222.22-.549t-.22-.547q-.223-.22-.55-.22t-.548.22q-.22.222-.22.55t.222.547t.549.22t.548-.22M17.077 22V3z");
}

</style>
