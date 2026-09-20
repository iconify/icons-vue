<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zegwcyysn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zegwcyysn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:three-circles-fill" /></template>
