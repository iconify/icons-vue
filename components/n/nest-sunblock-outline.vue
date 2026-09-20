<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ludtk2b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-sunblock-outline" /></template>
<style>
.ludtk2b0k {
  fill: currentColor;
  d: path("M2.5 7.039V4.5h1v2.539zm0 12.461v-2.538h1V19.5zM6.866 8.848l-.714-.714L7.95 6.337l.714.713zm1.084 8.815l-1.798-1.798l.714-.713l1.798 1.798zm.07-5.163v-1H15l-2.108-2.804l.812-.604l2.327 3.116q.298.404.077.848t-.723.444zm12.002 6q-.416 0-.71-.292q-.293-.291-.293-.708v-11q0-.417.291-.708q.291-.292.707-.292t.709.292t.293.708v11q0 .417-.29.708q-.292.292-.707.292m-17.464-3v-1q1.031 0 1.765-.735q.735-.736.735-1.769t-.735-1.764T2.558 9.5v-1q1.458 0 2.479 1.021q1.02 1.021 1.02 2.479t-1.02 2.479Q4.016 15.5 2.557 15.5");
}

</style>
