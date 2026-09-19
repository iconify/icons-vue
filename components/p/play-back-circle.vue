<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xblyoz06u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xblyoz06u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:play-back-circle" /></template>
