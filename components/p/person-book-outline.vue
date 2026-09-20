<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh2wbmx4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:person-book-outline" /></template>
<style>
.kh2wbmx4b {
  fill: currentColor;
  d: path("M12 18q-1.4 0-2.675.438T7 19.75V20h10v-.25q-1.05-.875-2.325-1.312T12 18m3.225-1.475Q16.725 17.05 18 18V4H6v14q1.275-.95 2.775-1.475T12 16t3.225.525m-4.287-4.962q-.438-.438-.438-1.063t.438-1.062T12 9t1.063.438t.437 1.062t-.437 1.063T12 12t-1.062-.437M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm8.475-9.025Q15.5 11.95 15.5 10.5t-1.025-2.475T12 7T9.525 8.025T8.5 10.5t1.025 2.475T12 14t2.475-1.025M12 10.5");
}

</style>
