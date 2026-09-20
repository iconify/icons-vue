<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xted9krxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xted9krxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:observer-ai-light" /></template>
