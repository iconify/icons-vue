<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnyr25b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnyr25b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:send-cancel" /></template>
