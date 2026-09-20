<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew2dh5b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ew2dh5b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:observer-ai" /></template>
