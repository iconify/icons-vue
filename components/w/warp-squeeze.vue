<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ooaab7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e2ooaab7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:warp-squeeze" /></template>
