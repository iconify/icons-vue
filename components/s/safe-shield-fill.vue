<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfz1bwggw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfz1bwggw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-shield-fill" /></template>
