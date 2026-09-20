<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysth-06qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ysth-06qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ovh" /></template>
