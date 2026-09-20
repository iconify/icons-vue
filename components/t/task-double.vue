<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gpwbhrmwg.css';
import '../../css/o/ozhoyrbed.css';
import '../../css/l/lryotrmjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gpwbhrmwg"/><path class="ozhoyrbed"/><path class="lryotrmjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:task-double" /></template>
