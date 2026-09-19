<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxm12dbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxm12dbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vtmgo" /></template>
