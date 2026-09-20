<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9b65p45j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w9b65p45j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:play" /></template>
