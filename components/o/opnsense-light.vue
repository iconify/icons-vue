<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tskkj_7-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tskkj_7-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opnsense-light" /></template>
