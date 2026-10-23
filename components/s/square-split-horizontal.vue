<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqhh8rxsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqhh8rxsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-split-horizontal" /></template>
