<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/z/zqaivibei.css';
import '../../css/i/irh34pbvi.css';
import '../../css/z/zmax5t0cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="zqaivibei"/><path class="irh34pbvi"/><path class="zmax5t0cq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message-time" /></template>
