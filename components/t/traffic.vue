<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlnk3prhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:traffic" /></template>
<style>
.tlnk3prhe {
  fill: currentColor;
  d: path("M12.739 17.3q.319-.314.319-.796q0-.481-.315-.8t-.796-.32t-.8.315q-.32.315-.32.796t.315.801t.796.32t.8-.315m0-4.5q.32-.315.32-.796t-.315-.801t-.796-.32t-.8.315t-.32.796t.315.801t.796.32t.8-.315m0-4.5q.32-.315.32-.796t-.315-.801t-.796-.32t-.8.315t-.32.797t.315.8t.796.32t.8-.315m-4.796 6.93v-2.342q-.967-.235-1.445-.872q-.478-.636-.478-1.401h1.923V8.273q-.967-.235-1.445-.871Q6.019 6.765 6.019 6h1.923v-.923q0-.518.294-.797T8.942 4h6q.413 0 .706.28t.294.797V6h2.039q0 .766-.536 1.402q-.535.637-1.503.871v2.343h2.039q0 .765-.536 1.401q-.535.637-1.503.872v2.342h2.039q0 .765-.536 1.402q-.535.636-1.503.87V19q0 .413-.293.706t-.707.294h-6q-.412 0-.706-.294T7.942 19v-1.496q-.967-.235-1.445-.871q-.478-.637-.478-1.402z");
}

</style>
