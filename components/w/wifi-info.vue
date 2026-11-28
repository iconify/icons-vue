<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7rb8xakk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7rb8xakk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wifi-info" /></template>
