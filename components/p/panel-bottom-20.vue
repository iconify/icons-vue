<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofts-6g4o.css';
import '../../css/g/goolytbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofts-6g4o"/><path class="goolytbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-bottom-20" /></template>
