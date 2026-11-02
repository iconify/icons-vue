<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs2_t7lkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs2_t7lkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pen-ai-fill" /></template>
