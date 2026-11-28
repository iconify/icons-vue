<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6th-8ofz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6th-8ofz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pi" /></template>
