<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r5rnlpo5e.css';
import '../../css/r/rmhzubc9s.css';
import '../../css/e/eq7n5wb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="r5rnlpo5e"/><circle class="rmhzubc9s"/><path class="eq7n5wb5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sim-card" /></template>
