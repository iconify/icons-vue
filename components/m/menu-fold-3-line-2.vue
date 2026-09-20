<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy9yn_biv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy9yn_biv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-fold-3-line-2" /></template>
