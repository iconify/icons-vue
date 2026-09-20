<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6r95vbrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d6r95vbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:north-pole-security-dark" /></template>
