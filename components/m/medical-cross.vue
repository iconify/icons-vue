<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiu326fvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiu326fvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:medical-cross" /></template>
