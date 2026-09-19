<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwzqo-bou.css';
import '../../css/d/dt1emtbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kwzqo-bou"/><path class="dt1emtbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:return-down-back" /></template>
