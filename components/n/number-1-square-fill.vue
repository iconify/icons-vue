<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7cj1lbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o7cj1lbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-1-square-fill" /></template>
