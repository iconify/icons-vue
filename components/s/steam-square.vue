<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf8qucwjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="hf8qucwjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:steam-square" /></template>
