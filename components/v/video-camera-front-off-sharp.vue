<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leb2ahyna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-camera-front-off-sharp" /></template>
<style>
.leb2ahyna {
  fill: currentColor;
  d: path("m20.577 15.77l-3.039-3.04v2.118L7.692 5h9.848v6.27l3.038-3.04zm-1.18 5.196L2.418 3.988l.708-.708l16.977 16.977zM4.884 5.037L17.5 17.655V19H3.539V5.039zm2.288 10.27h6.616v-.166q0-.792-.937-1.313t-2.371-.521t-2.371.52q-.937.522-.937 1.314z");
}

</style>
