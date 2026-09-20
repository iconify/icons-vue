<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-mthxbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-mthxbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-centerline-dashed-vertical" /></template>
