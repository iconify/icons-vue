<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4nb15djs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4nb15djs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tree-plus" /></template>
