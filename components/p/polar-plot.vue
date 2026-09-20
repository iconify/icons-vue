<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtery-rhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qtery-rhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:polar-plot" /></template>
