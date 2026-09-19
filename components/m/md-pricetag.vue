<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5_q_wbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5_q_wbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-pricetag" /></template>
