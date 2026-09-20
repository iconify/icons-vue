<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj8ffr3au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:running-with-errors-sharp" /></template>
<style>
.mj8ffr3au {
  fill: currentColor;
  d: path("M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2q2.2 0 4.163.9t3.387 2.55L12 13V4Q8.65 4 6.325 6.325T4 12t2.325 5.675T12 20q1.725 0 3.3-.712T18 17.25V20q-1.325.95-2.85 1.475T12 22m8-4v-8h2v8zm.288 3.713Q20 21.425 20 21t.288-.712T21 20t.713.288T22 21t-.288.713T21 22t-.712-.288");
}

</style>
