<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcardlb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bcardlb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:workspace-trusted" /></template>
