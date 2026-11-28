<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u52k2yfwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u52k2yfwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:wc-light" /></template>
