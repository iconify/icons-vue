<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg69hcbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lg69hcbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:star-large-outline" /></template>
