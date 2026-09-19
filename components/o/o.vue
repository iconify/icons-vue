<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di82h1dsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="di82h1dsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:o" /></template>
