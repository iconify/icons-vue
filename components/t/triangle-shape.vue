<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ote8ubydv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ote8ubydv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:triangle-shape" /></template>
