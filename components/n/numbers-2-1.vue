<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wud-c2bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wud-c2bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-2-1" /></template>
