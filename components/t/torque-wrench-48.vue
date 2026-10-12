<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xywdqfbfw.css';
import '../../css/w/wmfwlabqo.css';
import '../../css/h/hrs6edb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xywdqfbfw"/><path class="wmfwlabqo"/><path class="hrs6edb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:torque-wrench-48" /></template>
