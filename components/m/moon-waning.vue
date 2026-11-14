<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn2k2i2qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:moon-waning" /></template>
<style>
.fn2k2i2qg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.748 21.728q3.56-.243 6.147-2.832Q21.751 16.039 21.75 12q.001-4.039-2.855-6.896q-2.587-2.589-6.147-2.832q-3.757-.397-6.888 2.069Q2.143 7.269 2.143 12t3.717 7.659q3.131 2.466 6.888 2.069");
}

</style>
