<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8v7zs.css';
import '../../css/x/xy0gvz.css';
import '../../css/s/so-from-28.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8v7zs"/><path class="xy0gvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:paint-drop-half-twotone" /></template>
