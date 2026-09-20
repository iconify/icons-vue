<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k_xc25b3t"/><path class="s-tet24zz"/><path class="dnklo5bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:opensearch-icon" /></template>
<style>
.dnklo5bue {
  fill: var(--svg-color--005eb8, #005eb8);
  d: path("M15.674 56C6.971 70.198-1.446 89.129.21 115.632c3.43 54.899 53.154 96.546 100.108 92.033c18.38-1.767 37.255-16.75 35.578-43.587c-.729-11.662-6.437-18.546-15.714-23.838c-8.83-5.037-20.173-8.228-33.033-11.844c-15.534-4.37-33.553-9.277-47.401-19.483C23.15 96.682 11.804 82.503 15.674 56");
}

.k_xc25b3t {
  fill: var(--svg-color--005eb8, #005eb8);
  d: path("M246.95 94a9.05 9.05 0 0 0-9.05 9.05c0 74.476-60.374 134.85-134.85 134.85a9.05 9.05 0 1 0 0 18.1C187.522 256 256 187.522 256 103.05a9.05 9.05 0 0 0-9.05-9.05");
}

.s-tet24zz {
  fill: var(--svg-color--003b5c, #003b5c);
  d: path("M192.326 152c8.703-14.198 17.12-33.129 15.464-59.632C204.36 37.47 154.636-4.179 107.682.335c-18.38 1.767-37.255 16.75-35.578 43.587c.729 11.662 6.437 18.546 15.714 23.838c8.83 5.037 20.173 8.228 33.033 11.844c15.534 4.37 33.553 9.277 47.401 19.483c16.598 12.231 27.944 26.41 24.074 52.913");
}

</style>
