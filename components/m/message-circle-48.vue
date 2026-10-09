<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx58fm3og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lx58fm3og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-circle-48" /></template>
