<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzy0f__1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tzy0f__1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:refused" /></template>
