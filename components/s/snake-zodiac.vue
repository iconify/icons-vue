<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3ivccum.css';
import '../../css/m/m3ts_9bhm.css';
import '../../css/j/j2irmjbol.css';
import '../../css/b/bwcra3bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="m3ts_9bhm"/><path class="j2irmjbol"/><path class="bwcra3bfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:snake-zodiac" /></template>
