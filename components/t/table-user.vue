<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xps3pd9pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xps3pd9pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-user" /></template>
