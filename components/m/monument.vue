<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujk5wwbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ujk5wwbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:monument" /></template>
