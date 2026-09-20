<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-g18w0dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e-g18w0dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ringlink-light" /></template>
