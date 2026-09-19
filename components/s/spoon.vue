<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx2i-ob8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx2i-ob8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:spoon" /></template>
