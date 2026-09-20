<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riei8-yoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="riei8-yoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:multiplier-1" /></template>
