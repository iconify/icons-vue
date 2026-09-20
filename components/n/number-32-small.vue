<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdf92kcro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdf92kcro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-32-small" /></template>
