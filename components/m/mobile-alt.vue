<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyn9tsk4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="jyn9tsk4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:mobile-alt" /></template>
