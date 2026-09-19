<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ous1cc4fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ous1cc4fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:paved-road-alt-outline-24px" /></template>
