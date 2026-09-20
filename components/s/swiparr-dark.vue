<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5r16bcmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5r16bcmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swiparr-dark" /></template>
