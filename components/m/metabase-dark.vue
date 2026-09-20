<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eni8eiben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eni8eiben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metabase-dark" /></template>
