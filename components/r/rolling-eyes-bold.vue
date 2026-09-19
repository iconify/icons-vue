<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/on2p_wi5n.css';
import '../../css/v/v3y-9vz7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="on2p_wi5n"/><path clip-rule="evenodd" class="v3y-9vz7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:rolling-eyes-bold" /></template>
