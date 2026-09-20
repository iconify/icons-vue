<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/curtq7b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="curtq7b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tag-with-shekel" /></template>
