<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpw3oirif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpw3oirif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zoiper" /></template>
