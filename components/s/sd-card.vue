<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_llad4ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_llad4ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sd-card" /></template>
