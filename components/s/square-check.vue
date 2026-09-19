<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_5birbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_5birbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:square-check" /></template>
