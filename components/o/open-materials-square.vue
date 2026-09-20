<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q69k124zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="q69k124zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:open-materials-square" /></template>
