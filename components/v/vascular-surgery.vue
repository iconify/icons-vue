<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhfe5s5yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jhfe5s5yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:vascular-surgery" /></template>
