<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnym7qbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnym7qbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:visual-recognition" /></template>
