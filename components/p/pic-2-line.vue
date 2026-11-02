<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvpk04bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvpk04bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pic-2-line" /></template>
