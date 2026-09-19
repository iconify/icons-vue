<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuti-oq0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iuti-oq0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:square-large-outline" /></template>
