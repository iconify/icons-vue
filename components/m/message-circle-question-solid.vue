<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3vh0625f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3vh0625f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle-question-solid" /></template>
