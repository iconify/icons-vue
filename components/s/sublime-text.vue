<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr3fq8j0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":24};
const content = `<path class="kr3fq8j0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:sublime-text" /></template>
