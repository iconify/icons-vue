<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydsm8obkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydsm8obkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-zoom-in2-filled" /></template>
