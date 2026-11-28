<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os35jjbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os35jjbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ring" /></template>
