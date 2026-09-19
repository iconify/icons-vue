<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czs2bxbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="czs2bxbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whiteexclaimationmark" /></template>
