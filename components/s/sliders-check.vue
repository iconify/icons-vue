<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gilrvkbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gilrvkbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sliders-check" /></template>
