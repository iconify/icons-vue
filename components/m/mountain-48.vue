<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d33itbbpi.css';
import '../../css/j/jbxq4-b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d33itbbpi"/><path class="jbxq4-b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mountain-48" /></template>
