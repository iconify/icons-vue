<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7f8r1bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7f8r1bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-9-bold" /></template>
