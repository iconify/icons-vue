<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_8bvqb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="more-vertical-outline"><path class="Vector t_8bvqb7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:more-vertical-outline" /></template>
