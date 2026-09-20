<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9aztl2nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g9aztl2nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:shield" /></template>
