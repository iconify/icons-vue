<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpmm57b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpmm57b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:star-trek" /></template>
