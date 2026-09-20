<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvfgo8b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cvfgo8b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:play-stepwise-filled" /></template>
