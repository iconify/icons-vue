<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9uobpbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="l9uobpbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:mars-double" /></template>
