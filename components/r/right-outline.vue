<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3mve4_ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j3mve4_ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:right-outline" /></template>
