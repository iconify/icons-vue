<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9ou85b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ou85b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shopping-bag-minus" /></template>
