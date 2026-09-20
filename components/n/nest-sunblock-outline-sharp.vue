<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfpx_dzxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-sunblock-outline-sharp" /></template>
<style>
.mfpx_dzxm {
  fill: currentColor;
  d: path("M2.5 7.039V4.5h1v2.539zm0 12.461v-2.538h1V19.5zM6.866 8.848l-.714-.714L7.95 6.337l.714.713zm1.084 8.815l-1.798-1.798l.714-.713l1.798 1.798zm.07-5.163v-1H15l-2.108-2.804l.812-.604L17 12.5zm11 6v-13h2v13zm-16.462-3v-1q1.031 0 1.765-.735q.735-.736.735-1.769t-.735-1.764T2.558 9.5v-1q1.458 0 2.479 1.021q1.02 1.021 1.02 2.479t-1.02 2.479Q4.016 15.5 2.557 15.5");
}

</style>
