<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvnxxvb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fvnxxvb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tag-fill-20" /></template>
