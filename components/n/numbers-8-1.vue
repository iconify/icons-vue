<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4k57gbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4k57gbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-8-1" /></template>
