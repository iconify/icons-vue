<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coqe7zz9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="coqe7zz9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tablet" /></template>
