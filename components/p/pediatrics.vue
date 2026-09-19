<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n570r8b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n570r8b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pediatrics" /></template>
