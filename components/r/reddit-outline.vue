<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr87_k8po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pr87_k8po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:reddit-outline" /></template>
