<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txiucxbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txiucxbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openscad" /></template>
