<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4r1rlb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4r1rlb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rabbit-heart" /></template>
