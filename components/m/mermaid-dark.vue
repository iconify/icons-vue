<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qne3ze1at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qne3ze1at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mermaid-dark" /></template>
