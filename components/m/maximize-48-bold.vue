<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by36c192e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="by36c192e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:maximize-48-bold" /></template>
