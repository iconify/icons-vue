<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj7bijbti.css';
import '../../css/j/jsfpydcpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj7bijbti"/><path class="jsfpydcpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:medium-square" /></template>
