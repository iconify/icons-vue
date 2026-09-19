<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr2summni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hr2summni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:yin-yang" /></template>
