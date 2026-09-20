<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljkbb2b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ljkbb2b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tiktok-solid" /></template>
