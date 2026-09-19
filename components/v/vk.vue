<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmnkvqkdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":552,"height":384};
const content = `<path class="xmnkvqkdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:vk" /></template>
