<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8v7zs.css';
import '../../css/h/hakhof.css';
import '../../css/s/so-from-28.css';
import '../../css/f/fill-to-1.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8v7zs"/><path class="hakhof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:paint-drop-half-filled" /></template>
