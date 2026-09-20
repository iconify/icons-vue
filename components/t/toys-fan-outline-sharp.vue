<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlj96bc5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toys-fan-outline-sharp" /></template>
<style>
.zlj96bc5h {
  fill: currentColor;
  d: path("M12 12q0-1.91 1.372-3.282t3.282-1.372t3.282 1.372T21.308 12zm-7.935 3.282Q2.692 13.91 2.692 12H12q0 1.91-1.372 3.282t-3.282 1.372t-3.282-1.372M12 12q-1.91 0-3.282-1.372T7.346 7.346t1.372-3.282T12 2.692zm0 9.308V12q1.91 0 3.282 1.372t1.372 3.282t-1.372 3.282T12 21.308");
}

</style>
