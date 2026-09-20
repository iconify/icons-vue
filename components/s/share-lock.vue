<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik8qzi1hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ik8qzi1hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:share-lock" /></template>
