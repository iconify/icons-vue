<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu36pmbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eu36pmbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:project-scenarios" /></template>
