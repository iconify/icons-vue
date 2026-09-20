<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wemzwxcsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wemzwxcsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:waste-basket-14" /></template>
