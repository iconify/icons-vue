<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl151drgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl151drgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:uplabs" /></template>
