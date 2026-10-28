<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk8uo8bex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dk8uo8bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:n8n" /></template>
