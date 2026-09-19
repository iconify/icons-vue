<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g49kx7b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g49kx7b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:paperclip" /></template>
