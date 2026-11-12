<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgc5t8g4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgc5t8g4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pufferpanel-light" /></template>
