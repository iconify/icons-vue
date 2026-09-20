<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3fa7zbhj.css';
import '../../css/p/p5t4w3b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3fa7zbhj"/><path class="p5t4w3b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:view-square-bold" /></template>
