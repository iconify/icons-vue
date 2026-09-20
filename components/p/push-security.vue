<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3wb3mu3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d3wb3mu3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:push-security" /></template>
