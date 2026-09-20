<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubk2lab2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubk2lab2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-arrow-left" /></template>
