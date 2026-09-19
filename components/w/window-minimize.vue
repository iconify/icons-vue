<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc34xcctc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zc34xcctc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:window-minimize" /></template>
