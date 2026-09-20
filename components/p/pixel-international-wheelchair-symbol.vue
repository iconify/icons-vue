<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-94bibkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f-94bibkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-international-wheelchair-symbol" /></template>
