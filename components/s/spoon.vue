<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y472cnbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y472cnbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:spoon" /></template>
