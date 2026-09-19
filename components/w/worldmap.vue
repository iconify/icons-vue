<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr9e-ibdt.css';
import '../../css/a/ag80qrbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sr9e-ibdt"/><path class="ag80qrbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:worldmap" /></template>
