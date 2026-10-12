<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6hwh81nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f6hwh81nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-square-48" /></template>
