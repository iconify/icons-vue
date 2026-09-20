<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7ehs_32k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t7ehs_32k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:riven-light" /></template>
