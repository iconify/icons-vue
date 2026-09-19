<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euq48-b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="euq48-b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-shield" /></template>
