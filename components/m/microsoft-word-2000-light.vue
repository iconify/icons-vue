<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpwuex3wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dpwuex3wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-word-2000-light" /></template>
