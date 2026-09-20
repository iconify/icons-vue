<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4k2mib2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t4k2mib2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:star-empty-space" /></template>
