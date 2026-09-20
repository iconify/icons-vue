<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feki1l08y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feki1l08y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-0-1" /></template>
