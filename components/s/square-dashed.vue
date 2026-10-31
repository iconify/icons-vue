<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw8yxj55w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw8yxj55w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:square-dashed" /></template>
