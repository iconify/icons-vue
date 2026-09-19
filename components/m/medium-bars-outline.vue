<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccxcz9b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ccxcz9b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medium-bars-outline" /></template>
