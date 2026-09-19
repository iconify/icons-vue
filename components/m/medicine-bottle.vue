<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqmpb4b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dqmpb4b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medicine-bottle" /></template>
