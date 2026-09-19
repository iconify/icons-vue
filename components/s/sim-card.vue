<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g6vt25bsd.css';
import '../../css/r/rfkvs9bdx.css';
import '../../css/l/l_2ml6bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="g6vt25bsd"/><circle class="rfkvs9bdx"/><rect class="l_2ml6bep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:sim-card" /></template>
