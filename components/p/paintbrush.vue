<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa-bn8bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa-bn8bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:paintbrush" /></template>
