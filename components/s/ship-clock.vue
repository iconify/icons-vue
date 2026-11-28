<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxh-i38bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxh-i38bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ship-clock" /></template>
