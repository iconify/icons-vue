<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4_-n21gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4_-n21gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-padding-solid" /></template>
