<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x21i_4b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:square-circle-outline-sharp" /></template>
<style>
.x21i_4b4j {
  fill: currentColor;
  d: path("M7.5 16.5h9v-9h-9zm2-2v-5h5v5zm-1.4 6.713q-1.825-.788-3.175-2.138T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22t-3.9-.788M12 20q3.325 0 5.663-2.337T20 12t-2.337-5.663T12 4T6.337 6.338T4 12t2.338 5.663T12 20m0-8");
}

</style>
