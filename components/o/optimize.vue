<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3ivccum.css';
import '../../css/f/fja7r230c.css';
import '../../css/r/rlhd26bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="fja7r230c"/><path class="rlhd26bov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:optimize" /></template>
