<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpx6_37as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hpx6_37as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:threema" /></template>
