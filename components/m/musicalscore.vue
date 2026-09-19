<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2ubv2bis.css';
import '../../css/c/cbna_rb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h2ubv2bis"/><path class="cbna_rb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:musicalscore" /></template>
