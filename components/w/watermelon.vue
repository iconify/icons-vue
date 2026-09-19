<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8rrb8l5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l8rrb8l5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:watermelon" /></template>
