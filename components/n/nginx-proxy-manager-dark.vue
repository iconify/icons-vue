<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv-0_mbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cv-0_mbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nginx-proxy-manager-dark" /></template>
