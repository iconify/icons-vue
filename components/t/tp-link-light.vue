<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uys6emowx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uys6emowx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tp-link-light" /></template>
