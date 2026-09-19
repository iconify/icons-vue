<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frzcg76an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="frzcg76an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:x" /></template>
