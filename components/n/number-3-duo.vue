<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niubgw59c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niubgw59c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-3-duo" /></template>
