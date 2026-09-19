<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm7kog0ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm7kog0ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:skip-back" /></template>
