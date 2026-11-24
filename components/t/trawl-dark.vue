<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytca5ac7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ytca5ac7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trawl-dark" /></template>
