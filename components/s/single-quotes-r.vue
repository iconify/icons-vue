<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb7_vib4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb7_vib4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:single-quotes-r" /></template>
