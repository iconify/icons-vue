<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8z-qnb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8z-qnb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:robot-vacuum" /></template>
