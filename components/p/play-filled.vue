<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqcj7x-iu.css';
import '../../css/z/zgszk2b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sqcj7x-iu"/><path class="zgszk2b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:play-filled" /></template>
