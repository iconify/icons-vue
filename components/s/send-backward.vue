<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlr68im_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qlr68im_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:send-backward" /></template>
