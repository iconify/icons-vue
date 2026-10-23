<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqufedbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqufedbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:panel-top-dashed" /></template>
