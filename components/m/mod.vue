<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxg60abnf.css';
import '../../css/o/oajkybcsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sxg60abnf"/><path class="oajkybcsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:mod" /></template>
