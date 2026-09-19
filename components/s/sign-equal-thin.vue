<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp9ahgblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp9ahgblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-equal-thin" /></template>
