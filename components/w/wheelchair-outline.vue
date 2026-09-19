<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy0eyp0kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iy0eyp0kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:wheelchair-outline" /></template>
