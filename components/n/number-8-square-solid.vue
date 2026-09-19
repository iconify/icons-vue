<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktvcx-7jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktvcx-7jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:number-8-square-solid" /></template>
