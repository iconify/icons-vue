<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjdl1fw-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hjdl1fw-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rocket-chat-light" /></template>
