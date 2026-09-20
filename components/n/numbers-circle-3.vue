<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/q/qcln40b5r.css';
import '../../css/g/g25uthmua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="shu3xdl9q"/><circle class="qcln40b5r"/><path class="g25uthmua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-circle-3" /></template>
