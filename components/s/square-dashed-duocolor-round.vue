<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxiuv0pbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxiuv0pbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-duocolor-round" /></template>
