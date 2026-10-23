<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg5qm8m1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg5qm8m1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sword" /></template>
