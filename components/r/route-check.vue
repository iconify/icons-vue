<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9rdg7ejj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9rdg7ejj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:route-check" /></template>
