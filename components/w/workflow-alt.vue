<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd56lrbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd56lrbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:workflow-alt" /></template>
