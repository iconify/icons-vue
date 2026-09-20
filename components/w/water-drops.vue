<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3v5ifs0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-drops" /></template>
<style>
.x3v5ifs0p {
  fill: currentColor;
  d: path("M12 21q-3.002 0-5.001-2.061T5 13.8q0-2.154 1.738-4.765T12 3.308q.521.46.987.894q.465.435.924.889q-.701.884-1.248 1.968q-.548 1.083-.548 2.241q0 2.356 1.584 3.97t3.801 1.615q.362 0 .734-.061q.372-.06.722-.174q-.296 2.756-2.229 4.553T12 21m3.366-9.446Q14.5 10.608 14.5 9.3q0-.896.742-2.036T17.5 4.692q1.596 1.493 2.298 2.574q.702 1.082.702 2.034q0 1.308-.865 2.254q-.866.946-2.135.946t-2.134-.946m-3.149 7.138q.223-.025.35-.15q.125-.127.125-.311q0-.216-.148-.332t-.363-.091q-1.025.075-2.29-.64q-1.266-.714-1.566-2.39q-.05-.236-.166-.353q-.117-.117-.295-.117q-.197 0-.335.147t-.083.44q.387 2.082 1.923 2.98t2.848.817");
}

</style>
