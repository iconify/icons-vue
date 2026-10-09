<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk1y4abcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zk1y4abcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-48" /></template>
