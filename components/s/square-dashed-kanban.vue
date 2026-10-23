<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pti38wbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pti38wbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-dashed-kanban" /></template>
