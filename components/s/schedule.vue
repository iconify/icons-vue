<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3ivccum.css';
import '../../css/w/wy2fffbal.css';
import '../../css/p/pt3ta8bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><rect class="wy2fffbal"/><path class="pt3ta8bfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:schedule" /></template>
