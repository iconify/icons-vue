<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl140ibun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl140ibun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:warehouse" /></template>
