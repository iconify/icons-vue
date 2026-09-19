<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0mvlgb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n0mvlgb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:negative" /></template>
