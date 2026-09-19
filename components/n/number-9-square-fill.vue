<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuhtm-b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yuhtm-b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-9-square-fill" /></template>
