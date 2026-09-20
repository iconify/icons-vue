<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhb4zd4zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="mhb4zd4zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:squarespace" /></template>
