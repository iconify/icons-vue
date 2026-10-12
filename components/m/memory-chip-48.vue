<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq31kobat.css';
import '../../css/x/xcgq2ybhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rq31kobat"/><path class="xcgq2ybhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:memory-chip-48" /></template>
