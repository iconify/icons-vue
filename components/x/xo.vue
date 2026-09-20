<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2cj950ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2cj950ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xo" /></template>
