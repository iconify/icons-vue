<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3fsg2nac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-thermostat" /></template>
<style>
.m3fsg2nac {
  fill: currentColor;
  d: path("m8.475 15l2.7-4.775v-1.1H7.3v1.025h2.6l.05.075l-2.4 4.275zm7.638-.862q.637-.863.637-2.138t-.65-2.137T14.35 9q-1.125 0-1.762.863T11.95 12t.638 2.138T14.35 15t1.763-.862m-1.763-.163q-.65 0-.975-.587T13.05 12q0-.6.275-1.287t1.025-.688t1.025.688T15.65 12q0 .8-.325 1.388t-.975.587M12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
