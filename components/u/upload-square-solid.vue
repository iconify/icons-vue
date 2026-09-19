<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycdgytbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ycdgytbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:upload-square-solid" /></template>
