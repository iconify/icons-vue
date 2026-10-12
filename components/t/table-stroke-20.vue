<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncd4tklcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ncd4tklcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:table-stroke-20" /></template>
