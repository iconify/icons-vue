<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfjdfu15i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bfjdfu15i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:openai" /></template>
