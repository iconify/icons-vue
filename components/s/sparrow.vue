<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw4f9jbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zw4f9jbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sparrow" /></template>
