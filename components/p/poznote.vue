<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyr6ptbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qyr6ptbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:poznote" /></template>
