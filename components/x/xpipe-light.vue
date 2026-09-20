<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb9r1gbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xb9r1gbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xpipe-light" /></template>
