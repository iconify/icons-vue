<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vggs3v5pz.css';
import '../../css/r/rkl8mz6zh.css';
import '../../css/q/q8l603bxd.css';
import '../../css/r/runcquzpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vggs3v5pz"/><path class="rkl8mz6zh"/><path class="q8l603bxd"/><path class="runcquzpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:readarr" /></template>
