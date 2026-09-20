<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue95yqnpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ue95yqnpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ontology-filled" /></template>
