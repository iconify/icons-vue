<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dugwl5byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dugwl5byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:smoking-area-solid" /></template>
