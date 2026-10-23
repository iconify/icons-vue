<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7bhmdbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7bhmdbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:unfold-horizontal" /></template>
