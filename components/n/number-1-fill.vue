<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0z_3kboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0z_3kboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-1-fill" /></template>
