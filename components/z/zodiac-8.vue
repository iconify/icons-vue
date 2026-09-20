<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvomfubey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pvomfubey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:zodiac-8" /></template>
