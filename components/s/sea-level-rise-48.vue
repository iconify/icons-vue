<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz02pm04a.css';
import '../../css/u/ucu3b4dxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jz02pm04a"/><path class="ucu3b4dxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sea-level-rise-48" /></template>
