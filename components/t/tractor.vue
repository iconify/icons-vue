<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qokzllbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qokzllbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tractor" /></template>
