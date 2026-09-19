<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yltp1rbuh.css';
import '../../css/d/drnbxkbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer yltp1rbuh"/><path class="drnbxkbxp duoicon-primary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:user-card" /></template>
