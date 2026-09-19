<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m32k1ef5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m32k1ef5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:menu-select" /></template>
