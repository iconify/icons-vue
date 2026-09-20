<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3oj0qnnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3oj0qnnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:vertical-slider-2" /></template>
