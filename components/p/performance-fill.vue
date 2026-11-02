<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5u2e8r8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5u2e8r8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:performance-fill" /></template>
