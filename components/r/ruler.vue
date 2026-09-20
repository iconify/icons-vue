<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thi1-bctc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="thi1-bctc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:ruler" /></template>
