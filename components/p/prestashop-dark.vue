<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry8bitgof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ry8bitgof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prestashop-dark" /></template>
