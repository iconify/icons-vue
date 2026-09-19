<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfzm8m2_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfzm8m2_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:pulse" /></template>
