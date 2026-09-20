<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn2b2unhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yn2b2unhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zscaler-dark" /></template>
