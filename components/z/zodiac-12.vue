<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr0n7--kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dr0n7--kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-12" /></template>
