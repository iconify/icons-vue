<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k01p36bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-cast-sharp" /></template>
<style>
.k01p36bte {
  fill: currentColor;
  d: path("M6 22v-1.384q.571 0 .978.406t.407.978zm3.77 0q0-1.573-1.099-2.671T6 18.23v-1q1.987 0 3.378 1.39T10.77 22zm3.384 0q0-2.984-2.085-5.07Q8.984 14.847 6 14.847v-1q1.692 0 3.18.642t2.589 1.743t1.743 2.589t.642 3.18zm-.566-15.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M17.077 22q-.385-2.134-1.296-4.053q-.912-1.918-2.309-3.36q-1.397-1.443-3.264-2.284Q8.34 11.461 6 11.461V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
