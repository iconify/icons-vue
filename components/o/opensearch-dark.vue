<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f67na1b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f67na1b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensearch-dark" /></template>
