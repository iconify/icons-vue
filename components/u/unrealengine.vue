<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/c/cn08i3b8i.css';
import '../../css/z/zxfkkwbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="d2kvgvbvc"><path class="cn08i3b8i"/><path class="zxfkkwbnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:unrealengine" /></template>
