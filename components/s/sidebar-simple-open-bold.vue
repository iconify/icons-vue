<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2wx7xb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h2wx7xb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-open-bold" /></template>
