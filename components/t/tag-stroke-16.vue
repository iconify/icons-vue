<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8rmcuiam.css';
import '../../css/j/jy4g_db5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a8rmcuiam"/><circle class="jy4g_db5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tag-stroke-16" /></template>
