<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3mszq0-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="x3mszq0-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:soccer-ball-o" /></template>
