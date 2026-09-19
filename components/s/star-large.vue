<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhumq9bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nhumq9bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:star-large" /></template>
