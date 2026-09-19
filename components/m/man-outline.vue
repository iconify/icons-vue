<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybjb7-_9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ybjb7-_9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:man-outline" /></template>
