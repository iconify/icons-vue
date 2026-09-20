<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe38t4jqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oe38t4jqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radicale-light" /></template>
