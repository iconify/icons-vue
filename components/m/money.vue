<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s34_ysbgj.css';
import '../../css/l/l5ntip6-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s34_ysbgj"/><path class="l5ntip6-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:money" /></template>
