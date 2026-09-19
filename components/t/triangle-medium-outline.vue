<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up0ti3bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="up0ti3bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:triangle-medium-outline" /></template>
