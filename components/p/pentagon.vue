<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft4g341fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ft4g341fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:pentagon" /></template>
