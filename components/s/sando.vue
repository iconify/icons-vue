<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rccltgwpt.css';
import '../../css/b/bg4qdp5ho.css';
import '../../css/o/o-2211bzh.css';
import '../../css/v/vg5zmbblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rccltgwpt"/><path class="bg4qdp5ho"/><path class="o-2211bzh"/><path class="vg5zmbblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sando" /></template>
