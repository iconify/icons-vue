<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_zinnm-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":384};
const content = `<path class="u_zinnm-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:minus" /></template>
