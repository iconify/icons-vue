<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxwun1osp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxwun1osp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:slash-diamond" /></template>
