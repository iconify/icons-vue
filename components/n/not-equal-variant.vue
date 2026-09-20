<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbp53x0bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbp53x0bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:not-equal-variant" /></template>
