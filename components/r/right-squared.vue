<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj8hzfb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hj8hzfb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:right-squared" /></template>
