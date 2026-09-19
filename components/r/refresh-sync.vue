<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivh42bn2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":480};
const content = `<path class="ivh42bn2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:refresh-sync" /></template>
