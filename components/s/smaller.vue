<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmpnrlbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lmpnrlbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:smaller" /></template>
