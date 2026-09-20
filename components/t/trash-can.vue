<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zur0szh7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zur0szh7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:trash-can" /></template>
