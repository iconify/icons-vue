<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpd3-cc6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpd3-cc6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:wrench" /></template>
