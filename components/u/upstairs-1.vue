<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt0mlvbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt0mlvbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:upstairs-1" /></template>
