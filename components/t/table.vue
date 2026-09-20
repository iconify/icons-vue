<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm1n4pbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm1n4pbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:table" /></template>
