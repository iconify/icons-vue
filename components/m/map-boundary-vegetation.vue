<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5h-uebpt.css';
import '../../css/q/q74q21bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k5h-uebpt"/><path class="q74q21bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:map-boundary-vegetation" /></template>
