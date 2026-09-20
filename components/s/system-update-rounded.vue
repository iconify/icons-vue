<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awcgcdcuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:system-update-rounded" /></template>
<style>
.awcgcdcuh {
  fill: currentColor;
  d: path("M7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.69.463-1.152T7.616 2h8.846q.67 0 1.143.472q.472.472.472 1.144V6.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31v9.869q0 .67-.472 1.143q-.472.472-1.143.472zm4.682-7.074q.137-.053.268-.184l2.388-2.388q.14-.14.153-.341t-.153-.367q-.16-.16-.351-.162t-.357.156L12.5 13.38V9.193q0-.213-.143-.357T12 8.692t-.357.143t-.143.357v4.189l-1.746-1.74q-.14-.141-.341-.15q-.202-.01-.367.155q-.16.16-.16.354t.16.354l2.388 2.388q.132.131.268.184q.137.053.298.053t.298-.053");
}

</style>
