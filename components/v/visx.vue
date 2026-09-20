<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjb_o1gxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjb_o1gxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:visx" /></template>
