<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5-6tkbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5-6tkbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reflect-vertical-alt" /></template>
