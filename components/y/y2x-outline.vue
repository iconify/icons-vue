<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvi3ftn6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hvi3ftn6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:y2x-outline" /></template>
