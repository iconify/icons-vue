<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo-1d-f3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eo-1d-f3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pound" /></template>
