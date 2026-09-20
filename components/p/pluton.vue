<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoir4ebcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yoir4ebcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pluton" /></template>
