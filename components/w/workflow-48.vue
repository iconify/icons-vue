<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntf6lmu1o.css';
import '../../css/z/zo2elrbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ntf6lmu1o"/><path class="zo2elrbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:workflow-48" /></template>
