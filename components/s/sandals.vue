<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs6i5vbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs6i5vbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:sandals" /></template>
