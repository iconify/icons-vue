<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh9zi52ew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh9zi52ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-5-box-outline" /></template>
