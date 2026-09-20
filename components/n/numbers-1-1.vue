<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu80dudss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu80dudss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-1-1" /></template>
