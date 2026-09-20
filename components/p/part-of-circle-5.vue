<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3gi5bchw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3gi5bchw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:part-of-circle-5" /></template>
