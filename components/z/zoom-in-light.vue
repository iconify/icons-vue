<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt0ma64ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt0ma64ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:zoom-in-light" /></template>
