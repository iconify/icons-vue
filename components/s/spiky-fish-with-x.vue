<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfdcb-bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jfdcb-bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spiky-fish-with-x" /></template>
