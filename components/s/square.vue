<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz71kybyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="rz71kybyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:square" /></template>
