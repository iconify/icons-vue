<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwtn6rbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wwtn6rbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort-amount-down" /></template>
