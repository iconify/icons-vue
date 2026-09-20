<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j76xemwuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pending-sharp" /></template>
<style>
.j76xemwuu {
  fill: currentColor;
  d: path("M8.063 13.063Q8.5 12.625 8.5 12t-.437-1.062T7 10.5t-1.062.438T5.5 12t.438 1.063T7 13.5t1.063-.437m5 0q.437-.438.437-1.063t-.437-1.062T12 10.5t-1.062.438T10.5 12t.438 1.063T12 13.5t1.063-.437m5 0q.437-.438.437-1.063t-.437-1.062T17 10.5t-1.062.438T15.5 12t.438 1.063T17 13.5t1.063-.437M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
