<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht-s7mkzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1632};
const content = `<path class="ht-s7mkzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:naver" /></template>
