<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5g469imy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5g469imy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:squarespace" /></template>
