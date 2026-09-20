<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgd3xjm7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kgd3xjm7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:money-stack-outline" /></template>
