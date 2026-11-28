<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-s1ljbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-s1ljbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:medal-star" /></template>
