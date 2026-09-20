<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz8n4bbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vz8n4bbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:signoz-light" /></template>
