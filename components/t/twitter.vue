<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/youkbbcbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cls-1 youkbbcbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:twitter" /></template>
