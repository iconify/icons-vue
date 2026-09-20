<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xap8y3b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xap8y3b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:memorial-stone-with-star-of-david" /></template>
