<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy7_sib4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qy7_sib4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-circle-star-fill" /></template>
