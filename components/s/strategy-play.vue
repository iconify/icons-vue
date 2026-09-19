<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjf3h00br.css';
import '../../css/j/jm0mfbcid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wjf3h00br"/><path class="jm0mfbcid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:strategy-play" /></template>
