<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g75tt3k2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g75tt3k2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-arrow-down" /></template>
