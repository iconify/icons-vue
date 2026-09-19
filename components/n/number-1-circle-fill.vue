<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hznh8nbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hznh8nbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-1-circle-fill" /></template>
