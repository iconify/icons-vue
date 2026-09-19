<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3pi0ybal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1536};
const content = `<path class="r3pi0ybal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:user-times" /></template>
