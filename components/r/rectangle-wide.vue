<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d703htbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d703htbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rectangle-wide" /></template>
