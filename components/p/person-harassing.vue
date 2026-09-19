<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeos434il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jeos434il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-harassing" /></template>
