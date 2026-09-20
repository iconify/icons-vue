<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_h7tfngl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-charge-sharp" /></template>
<style>
.t_h7tfngl {
  fill: currentColor;
  d: path("m11.577 16.23l2.539-5.076h-1.693V7.769l-2.538 5.077h1.692zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
