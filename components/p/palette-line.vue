<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry40d-87g.css';
import '../../css/c/cj-4sbbcy.css';
import '../../css/c/cqj30chyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry40d-87g"/><path class="cj-4sbbcy"/><path class="cqj30chyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:palette-line" /></template>
