<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub_fq4b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ub_fq4b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:road" /></template>
