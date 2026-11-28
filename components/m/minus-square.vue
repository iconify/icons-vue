<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvin6b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwvin6b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:minus-square" /></template>
