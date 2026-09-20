<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwbta5htg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wwbta5htg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:pike" /></template>
