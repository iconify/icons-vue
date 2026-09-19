<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezyz04baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezyz04baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-3-square-fill" /></template>
