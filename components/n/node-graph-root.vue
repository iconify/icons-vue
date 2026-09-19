<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o44li7u2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o44li7u2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:node-graph-root" /></template>
