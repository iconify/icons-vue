<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8p1x2bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h8p1x2bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:school-circle-exclamation" /></template>
