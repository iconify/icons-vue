<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj1y5cbbe.css';
import '../../css/x/x1xqvkh1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jj1y5cbbe"/><path class="x1xqvkh1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:oscilloscope-48-bold" /></template>
