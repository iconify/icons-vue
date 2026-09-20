<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glrqkxbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="glrqkxbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spiral-labyrinth" /></template>
