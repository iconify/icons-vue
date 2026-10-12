<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co_xwekit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="co_xwekit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sprout-stroke-20" /></template>
