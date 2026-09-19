<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1xcecc-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1xcecc-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pin-slash" /></template>
