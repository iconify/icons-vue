<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcrd29b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcrd29b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:window-code-block" /></template>
