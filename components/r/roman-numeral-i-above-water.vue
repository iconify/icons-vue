<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qudpbqb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qudpbqb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-i-above-water" /></template>
