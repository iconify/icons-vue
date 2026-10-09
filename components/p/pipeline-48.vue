<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8dcesb7n.css';
import '../../css/s/sb555ccjn.css';
import '../../css/v/vtvsuobia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8dcesb7n"/><path class="sb555ccjn"/><path class="vtvsuobia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipeline-48" /></template>
