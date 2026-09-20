<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/q/qcln40b5r.css';
import '../../css/x/xw02ljb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="shu3xdl9q"/><circle class="qcln40b5r"/><path class="xw02ljb9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-circle-1" /></template>
