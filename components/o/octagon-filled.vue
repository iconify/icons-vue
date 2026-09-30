<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzb44pixj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzb44pixj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:octagon-filled" /></template>
