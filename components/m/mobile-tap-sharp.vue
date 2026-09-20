<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joq97bfog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-tap-sharp" /></template>
<style>
.joq97bfog {
  fill: currentColor;
  d: path("M3 21V10.558h10.442V21zM3 8.154q0-2.135 1.503-3.645Q6.006 3 8.153 3v1Q6.422 4 5.21 5.22Q4 6.44 4 8.154zm3.692 0q0-.603.42-1.032t1.042-.43v1.462zm1.519 6.462q.31 0 .52-.21t.211-.52t-.21-.521t-.52-.211t-.52.21t-.211.52t.21.52q.21.212.52.212m7.635-1.174V8.154h-5.288V3H21v10.442zm0 7.558v-1q1.713 0 2.934-1.207T20 15.846h1Q21 18 19.49 19.5T15.847 21m0-3.692v-1.462h1.462q0 .62-.43 1.04q-.429.422-1.032.422");
}

</style>
