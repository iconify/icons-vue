<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3ad9nb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m3ad9nb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:monitor-slash-bold" /></template>
