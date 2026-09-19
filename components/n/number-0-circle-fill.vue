<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_k02bocx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_k02bocx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-0-circle-fill" /></template>
