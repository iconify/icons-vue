<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbhaofgzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:screenshot-keyboard-outline-sharp" /></template>
<style>
.rbhaofgzr {
  fill: currentColor;
  d: path("M12 14q-.825 0-1.412-.587T10 12t.588-1.412T12 10t1.413.588T14 12t-.587 1.413T12 14m2.825.825Q16 13.65 16 12t-1.175-2.825T12 8T9.175 9.175T8 12t1.175 2.825T12 16t2.825-1.175M2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
