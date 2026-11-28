<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jalhqjb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jalhqjb9h primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:strikethrough-duotone" /></template>
