<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr5g2_dys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="rr5g2_dys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:swap-vertical" /></template>
