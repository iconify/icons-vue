<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzqt8ge1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yzqt8ge1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:star-of-life-solid" /></template>
