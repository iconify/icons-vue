<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex9paebyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ex9paebyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mosquito" /></template>
