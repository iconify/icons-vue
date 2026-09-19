<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp9481b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gp9481b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pediatric-surgery" /></template>
