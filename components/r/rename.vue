<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4vzzdoih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i4vzzdoih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rename" /></template>
