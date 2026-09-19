<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf0xtbtqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="uf0xtbtqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:table-1" /></template>
