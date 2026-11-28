<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7s-hxb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7s-hxb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-4" /></template>
