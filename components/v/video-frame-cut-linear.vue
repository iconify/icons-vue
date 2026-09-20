<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bc_yy0adh.css';
import '../../css/c/c8qz4oc-t.css';
import '../../css/j/jgmiltbod.css';
import '../../css/d/d01mapbla.css';
import '../../css/t/tt5jrshzt.css';
import '../../css/v/vqrmtubzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bc_yy0adh"/><path class="c8qz4oc-t"/><path class="jgmiltbod"/><path class="d01mapbla"/><path class="tt5jrshzt"/><path class="vqrmtubzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-cut-linear" /></template>
