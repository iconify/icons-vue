<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxr4c1iyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxr4c1iyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:npm-fill" /></template>
