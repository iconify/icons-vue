<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f23o3mbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f23o3mbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:pause" /></template>
