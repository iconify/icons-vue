<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef9rq8zxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ef9rq8zxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-face-mask-outline" /></template>
