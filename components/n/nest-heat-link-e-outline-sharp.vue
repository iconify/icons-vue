<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrexhncsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-heat-link-e-outline-sharp" /></template>
<style>
.xrexhncsk {
  fill: currentColor;
  d: path("M8.1 21.213q-1.825-.788-3.175-2.138T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22t-3.9-.788M12 20q3.325 0 5.663-2.337T20 12t-2.337-5.663T12 4T6.337 6.338T4 12t2.338 5.663T12 20m-2.825-5.175Q8 13.65 8 12t1.175-2.825T12 8t2.825 1.175T16 12t-1.175 2.825T12 16t-2.825-1.175");
}

</style>
