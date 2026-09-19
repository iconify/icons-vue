<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij8808ltb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij8808ltb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shopping-code-check" /></template>
