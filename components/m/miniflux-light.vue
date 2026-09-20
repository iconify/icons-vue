<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9ybud3eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s9ybud3eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:miniflux-light" /></template>
