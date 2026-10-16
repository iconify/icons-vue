<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlkz-3bot.css';
import '../../css/g/gx580lbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlkz-3bot"/><path class="gx580lbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ticket-check-48" /></template>
