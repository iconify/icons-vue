<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ealdmy0gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ealdmy0gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:timescale" /></template>
