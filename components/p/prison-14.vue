<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtt_77_2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wtt_77_2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:prison-14" /></template>
