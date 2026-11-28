<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zho1v3d8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zho1v3d8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:turtle-fill" /></template>
