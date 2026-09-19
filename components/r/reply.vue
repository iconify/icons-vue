<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq532pp3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq532pp3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:reply" /></template>
