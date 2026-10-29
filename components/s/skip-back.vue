<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wauz9obhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wauz9obhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:skip-back" /></template>
