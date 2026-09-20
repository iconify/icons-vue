<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcdy8nbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="lcdy8nbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:paint-roller-1" /></template>
