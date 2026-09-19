<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t24_l9b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t24_l9b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:toilet-paper-slash" /></template>
