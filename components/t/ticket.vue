<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxp47pdsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxp47pdsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:ticket" /></template>
