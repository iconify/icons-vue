<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woxu74yrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="woxu74yrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:prism-sharp" /></template>
