<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_fiq-zyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1024};
const content = `<path class="b_fiq-zyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:microscope" /></template>
