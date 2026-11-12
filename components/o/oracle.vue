<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/modagxbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="modagxbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oracle" /></template>
