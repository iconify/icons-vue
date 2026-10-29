<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifxi99bxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifxi99bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sliders-horizontal" /></template>
