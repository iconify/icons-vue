<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u_mqnb1oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:micro-python" /></template>
<style>
.u_mqnb1oo {
  d: path("M0 0h122.76v199.86h10.48V0H256v256h-56.14V56.14h-10.48V256H66.62V56.14l-10.48.375V256H0zm237.287 208.094h-14.971v25.45h14.97z");
}

</style>
