<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlkz-3bot.css';
import '../../css/n/n827cbx-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlkz-3bot"/><path class="n827cbx-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ticket-48" /></template>
