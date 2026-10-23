<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbd7dvebg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbd7dvebg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-kanban" /></template>
