<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5vx22b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w5vx22b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pneumonia" /></template>
