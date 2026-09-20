<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp1096bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:perm-camera-mic-outline-sharp" /></template>
<style>
.lp1096bdh {
  fill: currentColor;
  d: path("M9 21H2V5h5.15L9 3h6l1.85 2H22v16h-7v-2h5V7h-4.05l-1.825-2h-4.25L8.05 7H4v12h5zm2 0h2v-3.1q2.15-.35 3.575-2.012T18 12h-2q0 1.65-1.175 2.825T12 16t-2.825-1.175T8 12H6q0 2.225 1.425 3.888T11 17.9zm2.413-7.587Q14 12.825 14 12V8q0-.825-.587-1.412T12 6t-1.412.588T10 8v4q0 .825.588 1.413T12 14t1.413-.587M4 19h16z");
}

</style>
