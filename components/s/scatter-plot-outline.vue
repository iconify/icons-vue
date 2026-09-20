<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vac4_0hal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scatter-plot-outline" /></template>
<style>
.vac4_0hal {
  fill: currentColor;
  d: path("M14.646 18.892q-.877-.876-.877-2.123t.877-2.123t2.123-.877t2.123.877t.877 2.123t-.877 2.123q-.876.877-2.123.877t-2.123-.877m3.536-.71q.587-.588.587-1.413t-.587-1.412t-1.413-.588t-1.412.588t-.588 1.412t.588 1.413t1.412.587t1.413-.587m-13.074-2.29q-.877-.876-.877-2.123t.877-2.123q.876-.877 2.123-.877t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.123-.877m3.535-.71q.588-.588.588-1.413t-.588-1.412t-1.412-.588t-1.413.588t-.587 1.412t.587 1.413t1.413.587t1.412-.587m.234-6.674Q8 7.63 8 6.385t.877-2.123T11 3.385t2.123.877T14 6.385t-.877 2.123T11 9.385t-2.123-.877m3.535-.711Q13 7.21 13 6.385t-.588-1.413T11 4.384t-1.413.588T9 6.384t.587 1.413T11 8.384t1.412-.587M11 6.384");
}

</style>
