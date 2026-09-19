<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nw1imxzmc.css';
import '../../css/n/nx395txhc.css';
import '../../css/t/truy7mboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="nw1imxzmc"/><path class="nx395txhc"/><path class="truy7mboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:melon" /></template>
