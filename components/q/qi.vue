<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbqw558-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbqw558-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qi" /></template>
