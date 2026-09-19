<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6zyj1bnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="g6zyj1bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:school" /></template>
