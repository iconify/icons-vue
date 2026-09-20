<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ucf8wnbem.css';
import '../../css/y/y479ucc5d.css';
import '../../css/a/ayqtcwb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ucf8wnbem"/><path clip-rule="evenodd" class="y479ucc5d"/><path class="ayqtcwb2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:upload-track-duotone" /></template>
