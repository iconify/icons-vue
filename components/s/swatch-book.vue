<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz2-nnb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz2-nnb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:swatch-book" /></template>
