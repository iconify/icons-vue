<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f40ypprxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f40ypprxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:robot-vacuum-check" /></template>
