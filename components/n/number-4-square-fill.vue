<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttq0anb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ttq0anb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-4-square-fill" /></template>
