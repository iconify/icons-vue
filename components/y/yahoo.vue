<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txjma1b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="txjma1b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:yahoo" /></template>
