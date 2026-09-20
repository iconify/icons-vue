<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy9np2b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vy9np2b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:screen-smartphone" /></template>
