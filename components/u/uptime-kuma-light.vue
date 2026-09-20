<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvq1iklbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":622,"height":622};
const content = `<path class="dvq1iklbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptime-kuma-light" /></template>
