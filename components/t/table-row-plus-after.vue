<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhx2ux-1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhx2ux-1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-row-plus-after" /></template>
