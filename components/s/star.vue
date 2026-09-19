<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um53zxbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="um53zxbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:star" /></template>
