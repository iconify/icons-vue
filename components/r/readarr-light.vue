<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvxztnb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yvxztnb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:readarr-light" /></template>
