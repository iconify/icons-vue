<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrt0s6edx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zrt0s6edx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticc-dash-light" /></template>
