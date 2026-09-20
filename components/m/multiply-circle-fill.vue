<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2ncdo1bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2ncdo1bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:multiply-circle-fill" /></template>
