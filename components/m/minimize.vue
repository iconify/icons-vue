<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xebg60blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xebg60blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:minimize" /></template>
