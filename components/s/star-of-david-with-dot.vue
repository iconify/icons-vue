<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nepl70bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nepl70bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:star-of-david-with-dot" /></template>
