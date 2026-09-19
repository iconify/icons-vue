<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7ri-jboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":583,"height":716};
const content = `<path class="p7ri-jboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:undo" /></template>
