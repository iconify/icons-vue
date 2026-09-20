<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deuoqgbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="deuoqgbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portal-relay" /></template>
