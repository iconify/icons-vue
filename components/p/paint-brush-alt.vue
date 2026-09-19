<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9kngs9to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g9kngs9to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:paint-brush-alt" /></template>
