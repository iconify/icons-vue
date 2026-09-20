<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg99wcb4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qg99wcb4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-light" /></template>
