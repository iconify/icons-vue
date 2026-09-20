<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-44i5b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-5.5};
const content = `<path class="y-44i5b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:strikethrough" /></template>
