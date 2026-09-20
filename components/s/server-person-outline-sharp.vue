<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw0qb5bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:server-person-outline-sharp" /></template>
<style>
.kw0qb5bjg {
  fill: currentColor;
  d: path("M4 22V2h16v20h-5l-1-2h-4l-1 2zm2-2h1.75l1-2h6.5l1 2H18V4H6zm2-5h8v-.55q0-1.3-1.25-1.875T12 12t-2.75.575T8 14.45zm5.413-4.587Q14 9.825 14 9t-.587-1.412T12 7t-1.412.588T10 9t.588 1.413T12 11t1.413-.587M12 12");
}

</style>
