<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1sfr-bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w1sfr-bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:square-outline" /></template>
