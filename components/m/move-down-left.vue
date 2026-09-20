<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppsp0su1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppsp0su1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:move-down-left" /></template>
