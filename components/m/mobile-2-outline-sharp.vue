<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6c28kb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-2-outline-sharp" /></template>
<style>
.l6c28kb5u {
  fill: currentColor;
  d: path("M12.588 19.01q.22-.222.22-.55t-.222-.547t-.549-.22t-.548.22q-.22.223-.22.55t.222.548q.221.22.549.22t.548-.222M6 22V2h12.077v4.83H19v3.686h-.923V22zm1-1h10.077V3H7zm0 0V3z");
}

</style>
