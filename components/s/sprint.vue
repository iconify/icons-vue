<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wap2xvans.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wap2xvans"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sprint" /></template>
