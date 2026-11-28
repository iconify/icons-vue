<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpkulib9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpkulib9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:zodiac-aquarius-solid" /></template>
