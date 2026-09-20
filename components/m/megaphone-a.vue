<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/c7zkydbij.css';
import '../../css/c/ct9fr6bou.css';
import '../../css/s/shz66wb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c7zkydbij"/><path class="ct9fr6bou"/><path class="shz66wb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:megaphone-a" /></template>
