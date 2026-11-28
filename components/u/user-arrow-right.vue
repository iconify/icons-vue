<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eryr_sldj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eryr_sldj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-arrow-right" /></template>
