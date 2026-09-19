<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj0nmlbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xj0nmlbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:person2x-outline" /></template>
