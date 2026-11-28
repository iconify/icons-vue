<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yogix9bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yogix9bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:paw-heart" /></template>
