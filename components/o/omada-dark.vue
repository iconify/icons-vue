<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvf2hdcms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wvf2hdcms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:omada-dark" /></template>
