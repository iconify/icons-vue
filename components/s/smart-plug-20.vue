<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5l7ikz-n.css';
import '../../css/x/xsu5q83hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h5l7ikz-n"/><path class="xsu5q83hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-plug-20" /></template>
