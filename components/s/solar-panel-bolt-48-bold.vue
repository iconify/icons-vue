<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcny63jha.css';
import '../../css/o/ocydsvu6l.css';
import '../../css/x/xm577jbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bcny63jha"/><path class="ocydsvu6l"/><path class="xm577jbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-panel-bolt-48-bold" /></template>
