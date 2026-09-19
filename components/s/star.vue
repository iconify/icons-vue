<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa7ad-bhf.css';
import '../../css/u/uf38hibyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wa7ad-bhf"/><path class="uf38hibyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:star" /></template>
