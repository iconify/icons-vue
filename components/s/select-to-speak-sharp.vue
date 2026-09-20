<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv2a-j8tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:select-to-speak-sharp" /></template>
<style>
.qv2a-j8tr {
  fill: currentColor;
  d: path("M14.077 19.494v-1.05q2.077-.727 3.346-2.5t1.27-3.969t-1.27-3.97t-3.346-2.5v-1.05q2.485.797 4.05 2.86t1.565 4.66t-1.565 4.66t-4.05 2.86m-2.77-1.918L7.732 14H4.308v-4H7.73l3.577-3.577zm2.77-2.27V8.643q.848.55 1.29 1.449q.44.898.44 1.909q0 1.006-.45 1.882t-1.28 1.426M2 7V2h5v1H3v4zm15 15v-1h4v-4h1v5z");
}

</style>
