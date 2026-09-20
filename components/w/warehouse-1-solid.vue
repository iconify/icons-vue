<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7qqmifly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r7qqmifly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:warehouse-1-solid" /></template>
