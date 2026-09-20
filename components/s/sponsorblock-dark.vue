<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_gi64bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_gi64bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sponsorblock-dark" /></template>
