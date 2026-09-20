<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da1c7fbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="da1c7fbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:truck-filled" /></template>
