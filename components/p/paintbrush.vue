<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw0wrli5t.css';
import '../../css/p/pixrq9syg.css';
import '../../css/y/ybvkvjmwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tw0wrli5t"/><path class="pixrq9syg"/><path class="ybvkvjmwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:paintbrush" /></template>
