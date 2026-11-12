<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5r9gq3-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-sync-corner-fill-round" /></template>
<style>
.m5r9gq3-b {
  fill: currentColor;
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m1.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M18 15h.748a3.475 3.475 0 0 0-4.854 1.447a.999.999 0 1 1-1.788-.894a5.4 5.4 0 0 1 1.025-1.422a5.4 5.4 0 0 1 1.422-1.025a5.46 5.46 0 0 1 5.447.317V13a1 1 0 0 1 2 0v3a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2m-9 6H6a4 4 0 0 1 0-8h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m-1.99-5H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M14 21.577V22a1 1 0 0 1-2 0v-3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2h-.748a3.47 3.47 0 0 0 4.854-1.447a1 1 0 1 1 1.788.894a5.4 5.4 0 0 1-1.025 1.422a5.4 5.4 0 0 1-1.422 1.025A5.46 5.46 0 0 1 14 21.577");
}

</style>
