<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elril8byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="elril8byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nrk-tv-light" /></template>
