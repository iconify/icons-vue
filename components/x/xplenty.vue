<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q6lbwzi4d"/><path class="wtooo6hgm"/><path class="zrzchcchz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:xplenty" /></template>
<style>
.q6lbwzi4d {
  fill: var(--svg-color--fff, #FFF);
  d: path("M128 249.018C61.09 249.018 6.982 194.91 6.982 128S61.09 6.982 128 6.982S249.018 61.091 249.018 128c0 66.91-54.109 121.018-121.018 121.018Z");
}

.wtooo6hgm {
  fill: var(--svg-color--3f3f3f, #3F3F3F);
  d: path("M128 14.545c62.836 0 113.455 51.2 113.455 113.455c0 62.255-50.619 113.455-113.455 113.455S14.545 190.836 14.545 128S65.164 14.545 128 14.545ZM128 0C57.018 0 0 57.018 0 128s57.018 128 128 128s128-57.018 128-128S197.818 0 128 0Z");
}

.zrzchcchz {
  fill: var(--svg-color--0ab3e5, #0AB3E5);
  d: path("m74.473 119.273l23.272 18.618l32-52.364l40.728 65.164l22.109-17.455l24.436 36.073c5.818-12.8 10.473-27.927 10.473-42.473c0-55.272-43.636-98.909-98.91-98.909c-55.272 0-100.654 44.8-100.654 98.91c0 17.454 4.655 32 11.637 46.545l34.909-54.11Z");
}

</style>
