<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti4q6eknm.css';
import '../../css/r/r0nv15b5g.css';
import '../../css/b/bf_msp58c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="r0nv15b5g"/><path class="bf_msp58c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:wingsuit-flying" /></template>
