<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kperkrzwn"/><path class="nuvrc4buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-temple-hindu" /></template>
<style>
.kperkrzwn {
  fill: currentColor;
  d: path("M13.51 5h-3.02l-.6 2h4.22zm1.2 4H9.29l-.6 2h6.62zm1.2 4H8.09l-.6 2H4v5h5v-5h6v5h5v-5h-3.49z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.nuvrc4buo {
  fill: currentColor;
  d: path("M20 11v2h-2L15 3V1h-2v2h-2.03V1h-2v2.12L6 13H4v-2H2v11h9v-5h2v5h9V11zm-9.51-6h3.02l.6 2H9.89zm-1.2 4h5.42l.6 2H8.69zM20 20h-5v-5H9v5H4v-5h3.49l.6-2h7.82l.6 2H20z");
}

</style>
