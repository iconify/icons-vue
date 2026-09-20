<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohcpt2bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohcpt2bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rotate-left" /></template>
