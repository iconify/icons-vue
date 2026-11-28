<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu2agmstk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pu2agmstk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:ungroup-light" /></template>
