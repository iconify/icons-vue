<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yowci5pvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yowci5pvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:powerbi" /></template>
