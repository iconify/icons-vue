<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i80g1fkkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i80g1fkkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mkdocs-light" /></template>
