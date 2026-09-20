<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh1gm4byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zh1gm4byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:share-link-solid" /></template>
