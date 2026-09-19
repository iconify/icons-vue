<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cw7t2ddpt.css';
import '../../css/t/tpuop0bqq.css';
import '../../css/o/oa4z7jbas.css';
import '../../css/i/imw8tubjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cw7t2ddpt"/><path class="tpuop0bqq"/><path class="oa4z7jbas"/><path class="imw8tubjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:outbox-tray" /></template>
