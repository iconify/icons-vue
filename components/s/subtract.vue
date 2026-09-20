<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti0yokb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ti0yokb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:subtract" /></template>
