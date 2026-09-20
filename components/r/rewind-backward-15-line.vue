<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceznk2bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ceznk2bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-15-line" /></template>
