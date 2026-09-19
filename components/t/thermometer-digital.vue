<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4cg5bcvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g4cg5bcvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:thermometer-digital" /></template>
