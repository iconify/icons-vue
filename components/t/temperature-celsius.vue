<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0elrnbcf.css';
import '../../css/j/j5257yb9v.css';
import '../../css/y/ydnb04iod.css';
import '../../css/y/ymie1nvqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m0elrnbcf"/><circle class="j5257yb9v"/><path class="ydnb04iod"/><path class="ymie1nvqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:temperature-celsius" /></template>
