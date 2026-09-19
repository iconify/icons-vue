<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjpo16ghz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="rjpo16ghz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:snowflake-8" /></template>
