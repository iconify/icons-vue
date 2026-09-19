<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4zp6bl0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i4zp6bl0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:t-outline" /></template>
