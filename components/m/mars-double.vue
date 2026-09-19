<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyo01_bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1792};
const content = `<path class="hyo01_bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mars-double" /></template>
