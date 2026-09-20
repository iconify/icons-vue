<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kao65-mts.css';
import '../../css/x/xah9mvbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kao65-mts"/><path class="xah9mvbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xrsh-dark" /></template>
