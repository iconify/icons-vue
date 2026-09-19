<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1zcd-6-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="l1zcd-6-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:snapchat-square" /></template>
