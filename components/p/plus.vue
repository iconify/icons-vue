<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cap52ybmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1408};
const content = `<path class="cap52ybmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:plus" /></template>
