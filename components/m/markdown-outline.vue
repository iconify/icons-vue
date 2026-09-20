<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmhy4nbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xmhy4nbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:markdown-outline" /></template>
