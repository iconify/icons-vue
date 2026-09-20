<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy0q690mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy0q690mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pencil" /></template>
