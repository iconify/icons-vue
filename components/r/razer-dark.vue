<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs2ym3b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zs2ym3b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:razer-dark" /></template>
