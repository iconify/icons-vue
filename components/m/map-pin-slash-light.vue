<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9r02achd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i9r02achd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:map-pin-slash-light" /></template>
