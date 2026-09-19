<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g698s6blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g698s6blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:paint" /></template>
