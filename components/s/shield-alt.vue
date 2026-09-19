<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6r_tccsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6r_tccsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:shield-alt" /></template>
