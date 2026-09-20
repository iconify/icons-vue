<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yns7smjod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yns7smjod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ram-2-line" /></template>
