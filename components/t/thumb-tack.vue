<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6a1ky2xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1664};
const content = `<path class="i6a1ky2xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:thumb-tack" /></template>
