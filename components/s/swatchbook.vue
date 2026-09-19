<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6tw3_chu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a6tw3_chu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:swatchbook" /></template>
