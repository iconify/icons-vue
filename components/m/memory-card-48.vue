<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi5qdgtra.css';
import '../../css/o/owfc160qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oi5qdgtra"/><path class="owfc160qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:memory-card-48" /></template>
