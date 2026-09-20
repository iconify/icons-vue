<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjbno271j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjbno271j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-color-accent" /></template>
