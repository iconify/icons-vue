<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy0a09b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xy0a09b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:triangle-left" /></template>
