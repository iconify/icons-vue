<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idw5dccpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="idw5dccpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mitmproxy-light" /></template>
