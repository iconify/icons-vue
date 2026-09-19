<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxm51gybk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fxm51gybk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sberbank" /></template>
