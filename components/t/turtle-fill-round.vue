<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxqij-tjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxqij-tjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:turtle-fill-round" /></template>
