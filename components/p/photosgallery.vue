<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cjcap9bwy"/><path class="d2uky2bxz"/><path class="hwozkhn5f"/><path class="wvkh3xb2a"/><path class="msixtsp-q"/><path class="kpiw80g1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photosgallery" /></template>
<style>
.cjcap9bwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.316 36.396s-6.103 7.404-16.43-3c0 0 10.005-7.322 16.43 3");
}

.d2uky2bxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.598 28.935s-5.784 6.284-15.028-3.03c0 0 9.276-6.21 15.028 3.03");
}

.hwozkhn5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.977 21.967S14.12 27.86 5.9 19.579c0 0 7.963-5.828 13.077 2.388m7.385 9.749s.693-9.904 5.199-10.806c0 0 8.665 7.253-.245 15.486");
}

.kpiw80g1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.227 12.937c-2.04-3.196-4.666-4.568-7.77-4.248c-.424 1.6-.855 5.129 1.835 9.045m21.024 18.662s4.025 6.428 11.184 1.371");
}

.msixtsp-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.286 18.364s-.824-6.977 4.625-8.259c0 0 5.82 5.712-.934 11.862");
}

.wvkh3xb2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.79 24s.93-6.897 4.948-8.34c0 0 6.659 6.25.86 13.275");
}

</style>
