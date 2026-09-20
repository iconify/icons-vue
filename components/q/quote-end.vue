<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maa29hsla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maa29hsla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:quote-end" /></template>
