<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-la7-bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i-la7-bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:ungroup" /></template>
