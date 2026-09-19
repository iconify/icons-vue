<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg1pcqlsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cg1pcqlsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:x2x-outline" /></template>
