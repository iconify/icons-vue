<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-8nb7x6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-8nb7x6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:transform-1-filled" /></template>
