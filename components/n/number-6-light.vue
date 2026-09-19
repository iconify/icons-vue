<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgeizubcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgeizubcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-6-light" /></template>
