<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijdv2nm9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ijdv2nm9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ruler-diagonal" /></template>
