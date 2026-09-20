<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn5ibqeei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bn5ibqeei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:spiral-shape-remix" /></template>
