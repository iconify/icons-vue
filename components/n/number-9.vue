<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpfoe4jqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpfoe4jqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-9" /></template>
