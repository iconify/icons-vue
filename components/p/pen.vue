<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwbq6kw8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwbq6kw8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:pen" /></template>
