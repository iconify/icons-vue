<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgd5etdai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kgd5etdai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:staples-outline" /></template>
