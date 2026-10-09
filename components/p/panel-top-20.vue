<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofts-6g4o.css';
import '../../css/n/n0dt_tw8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofts-6g4o"/><path class="n0dt_tw8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-top-20" /></template>
