<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkzvp6b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:universal-local-sharp" /></template>
<style>
.tkzvp6b_v {
  fill: currentColor;
  d: path("M2 20V4h20v16zm9.288-8.287Q11 11.425 11 11t.288-.712T12 10t.713.288T13 11t-.288.713T12 12t-.712-.288M12 17q2.025-1.725 3.013-3.187T16 11.1q0-1.875-1.213-2.987T12 7T9.213 8.113T8 11.1q0 1.25.988 2.713T12 17");
}

</style>
