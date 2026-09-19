<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inje7ybsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inje7ybsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:priority-high-solid" /></template>
