<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1d3vglmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1d3vglmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plain-bold" /></template>
