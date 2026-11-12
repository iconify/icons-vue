<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeo-qubjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yeo-qubjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:system76-light" /></template>
