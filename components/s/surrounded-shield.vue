<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh-9gdc_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qh-9gdc_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:surrounded-shield" /></template>
