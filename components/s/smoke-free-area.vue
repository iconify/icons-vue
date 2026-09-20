<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u943xibiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u943xibiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:smoke-free-area" /></template>
