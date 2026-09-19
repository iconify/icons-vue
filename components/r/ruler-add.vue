<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwh8l9bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwh8l9bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ruler-add" /></template>
