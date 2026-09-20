<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di-ptib1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-drops-rounded" /></template>
<style>
.di-ptib1m {
  fill: currentColor;
  d: path("M12 21q-3.002 0-5.001-2.061T5 13.8q0-2.042 1.56-4.484t4.713-5.349q.298-.292.715-.304t.714.28q.31.298.61.576t.6.571q-.703.885-1.25 1.969q-.546 1.083-.546 2.241q0 2.356 1.583 3.97q1.584 1.615 3.801 1.615q.362 0 .734-.061q.372-.06.722-.174q-.296 2.756-2.229 4.553T12 21m3.366-9.446Q14.5 10.608 14.5 9.3q0-.835.618-1.854t1.922-2.305q.193-.187.46-.187t.46.187q1.34 1.317 1.94 2.293t.6 1.866q0 1.308-.865 2.254q-.866.946-2.135.946t-2.134-.946m-3.149 7.138q.223-.025.35-.15q.125-.127.125-.311q0-.216-.148-.332t-.363-.091q-1.025.075-2.29-.64q-1.266-.714-1.566-2.39q-.05-.236-.166-.353q-.117-.117-.295-.117q-.197 0-.335.147t-.083.44q.387 2.082 1.923 2.98t2.848.817");
}

</style>
