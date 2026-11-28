<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxrb4_bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cxrb4_bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-x-bold" /></template>
