<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqxfm3x3o.css';
import '../../css/r/rwuxsc6cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqxfm3x3o"/><path class="rwuxsc6cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:train-3" /></template>
