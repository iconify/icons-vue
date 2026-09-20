<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teizljb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="teizljb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-ahimsa-hand" /></template>
