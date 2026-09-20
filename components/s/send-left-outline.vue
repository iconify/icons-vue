<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7r-9rbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j7r-9rbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:send-left-outline" /></template>
