<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnzc5o18j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnzc5o18j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tag-2-fill" /></template>
