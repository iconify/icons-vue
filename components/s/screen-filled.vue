<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxb7hz46y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pxb7hz46y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:screen-filled" /></template>
