<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im61p5bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="im61p5bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-split-3x1" /></template>
