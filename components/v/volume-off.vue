<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz6g2ynyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="mz6g2ynyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:volume-off" /></template>
