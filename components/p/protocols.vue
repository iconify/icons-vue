<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh_vbsbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wh_vbsbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:protocols" /></template>
