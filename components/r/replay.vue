<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/llp4lcc-o.css';
import '../../css/d/devx4xt0b.css';
import '../../css/f/fltfvbcam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="llp4lcc-o"/><path class="devx4xt0b"/><path class="fltfvbcam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:replay" /></template>
