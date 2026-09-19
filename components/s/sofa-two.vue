<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ni8vhmowy.css';
import '../../css/y/y70606bue.css';
import '../../css/d/d-7iqjt6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="ni8vhmowy"/><path class="y70606bue"/><path clip-rule="evenodd" class="d-7iqjt6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sofa-two" /></template>
