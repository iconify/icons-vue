<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_s4zp7_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h_s4zp7_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shutdown" /></template>
