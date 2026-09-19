<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0_08ib8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0_08ib8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:movies-anywhere-text-vertical" /></template>
