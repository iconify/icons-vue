<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uad703_kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:square-circle-outline-rounded" /></template>
<style>
.uad703_kb {
  fill: currentColor;
  d: path("M8.5 16.5h7q.425 0 .713-.288t.287-.712v-7q0-.425-.288-.712T15.5 7.5h-7q-.425 0-.712.288T7.5 8.5v7q0 .425.288.713t.712.287m1-2v-5h5v5zm-1.4 6.713q-1.825-.788-3.175-2.138T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22t-3.9-.788M12 20q3.325 0 5.663-2.337T20 12t-2.337-5.663T12 4T6.337 6.338T4 12t2.338 5.663T12 20m0-8");
}

</style>
