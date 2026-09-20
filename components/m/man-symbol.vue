<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5e6vsrrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="l5e6vsrrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:man-symbol" /></template>
