<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymd4orbxh.css';
import '../../css/m/m7rus1bei.css';
import '../../css/v/vaiokxbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse transform="rotate(-45 256.001 304)" class="ymd4orbxh"/><path class="m7rus1bei"/><path class="vaiokxbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:train" /></template>
