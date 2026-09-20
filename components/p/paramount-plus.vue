<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn_k6cbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qn_k6cbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paramount-plus" /></template>
