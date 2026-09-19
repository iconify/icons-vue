<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj10r2b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hj10r2b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:psx" /></template>
