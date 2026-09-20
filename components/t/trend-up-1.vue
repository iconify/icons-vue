<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahn2rbxwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahn2rbxwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:trend-up-1" /></template>
