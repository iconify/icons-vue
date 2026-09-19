<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w04sejcqd.css';
import '../../css/s/s_xkkcbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w04sejcqd"/><path class="s_xkkcbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-scale" /></template>
