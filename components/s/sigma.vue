<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shd9aibgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shd9aibgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sigma" /></template>
