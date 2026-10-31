<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_oplqdxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_oplqdxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-round" /></template>
