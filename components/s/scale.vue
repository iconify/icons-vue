<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6-09cago.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6-09cago"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:scale" /></template>
