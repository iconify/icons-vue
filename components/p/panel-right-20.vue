<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofts-6g4o.css';
import '../../css/h/hvu33mbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ofts-6g4o"/><path class="hvu33mbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-right-20" /></template>
