<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndzm86bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-add-outline" /></template>
<style>
.ndzm86bff {
  fill: currentColor;
  d: path("M3 21L20.994 3.006v8.933q-.238-.103-.478-.16q-.241-.056-.522-.117V5.427L5.421 20h8.221q.124.287.26.527q.137.24.32.473zm15.5 0v-3h-3v-1h3v-3h1v3h3v1h-3v3zM5.421 20L19.994 5.427l-4.056 4.057l-3.372 3.37l-3.289 3.29z");
}

</style>
