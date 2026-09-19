<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngiba1bvc"/><path class="e41ip5b0d"/><path class="cchi1pvsz"/><path class="ek3-benoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-security-update-warning" /></template>
<style>
.cchi1pvsz {
  fill: currentColor;
  d: path("M17 1.01L7 1c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-1.99-2-1.99M17 21H7v-1h10zm0-3H7V6h10zm0-14H7V3h10z");
}

.e41ip5b0d {
  fill: currentColor;
  d: path("M11 15h2v2h-2zm0-8h2v6h-2z");
}

.ek3-benoy {
  fill: currentColor;
  d: path("M7 21h10v-1H7zM7 3v1h10V3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ngiba1bvc {
  fill: currentColor;
  d: path("M11 7h2v6h-2zm0 8h2v2h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
