<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjkq6u0-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":383,"height":854};
const content = `<path class="zjkq6u0-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:slash" /></template>
