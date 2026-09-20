<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxjkwp-4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-pump-sharp" /></template>
<style>
.mxjkwp-4e {
  fill: currentColor;
  d: path("m12 9l-.85 1.25q-.675 1.05-.913 1.613T10 13q0 .825.588 1.413T12 15t1.413-.587T14 13q0-.575-.238-1.137t-.912-1.613zm-4.425 7.425Q5.75 14.6 5.75 12t1.825-4.425T12 5.75t4.425 1.825T18.25 12t-1.825 4.425T12 18.25t-4.425-1.825M21 12v-1h-1.325q-.275-2-1.437-3.588T15.325 5H21V4h2v8zM1 20v-8h2v1h1.325q.275 2 1.438 3.588T8.675 19H3v1z");
}

</style>
