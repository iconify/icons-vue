<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jczf2_bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jczf2_bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:spoon" /></template>
