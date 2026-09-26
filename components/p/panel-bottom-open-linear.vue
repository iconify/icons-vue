<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e6ihngbuj.css';
import '../../css/b/b2vvr6bvh.css';
import '../../css/n/n9h5_9byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e6ihngbuj"/><path class="b2vvr6bvh"/><path class="n9h5_9byn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-bottom-open-linear" /></template>
