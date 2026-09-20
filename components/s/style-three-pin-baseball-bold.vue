<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obu_zh1ok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obu_zh1ok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:style-three-pin-baseball-bold" /></template>
