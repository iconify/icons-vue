<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow7mwmbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow7mwmbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rotate" /></template>
