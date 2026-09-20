<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/l/ljxcg8b7i.css';
import '../../css/m/mrt9bwk2y.css';
import '../../css/c/cww-bgbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path class="ljxcg8b7i"/><path class="mrt9bwk2y"/><path class="cww-bgbad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:opencv-dark" /></template>
