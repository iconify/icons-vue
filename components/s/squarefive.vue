<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k66dz5bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k66dz5bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarefive" /></template>
