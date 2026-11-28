<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1b940qxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b1b940qxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:page-break" /></template>
