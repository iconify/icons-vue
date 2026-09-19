<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p2qfbdb0a.css';
import '../../css/n/nsc284b_q.css';
import '../../css/a/argi97bmu.css';
import '../../css/r/rai6xtdfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="p2qfbdb0a"/><path class="nsc284b_q"/><path class="argi97bmu"/><path class="rai6xtdfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:mouse-face" /></template>
