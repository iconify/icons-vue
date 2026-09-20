<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c95rs2b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c95rs2b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scrutiny-dark" /></template>
