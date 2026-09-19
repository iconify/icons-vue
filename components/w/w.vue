<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixb90tb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ixb90tb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:w" /></template>
