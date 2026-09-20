<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsjuw5exz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dsjuw5exz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:strikethrough-outline" /></template>
