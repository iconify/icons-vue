<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj7a55boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zj7a55boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:tooltip-text" /></template>
