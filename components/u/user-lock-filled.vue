<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbn2yrbjm.css';
import '../../css/v/v82trt5er.css';
import '../../css/w/wtr3z9boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbn2yrbjm"/><path clip-rule="evenodd" class="v82trt5er"/><path class="wtr3z9boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-lock-filled" /></template>
