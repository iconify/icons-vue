<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq_-nnb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jq_-nnb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:miniflux-dark" /></template>
