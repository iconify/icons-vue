<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrus5xbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yrus5xbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mega-dark" /></template>
