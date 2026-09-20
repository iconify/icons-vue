<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd6x9ya9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd6x9ya9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tic-tac" /></template>
