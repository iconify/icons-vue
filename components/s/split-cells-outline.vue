<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgj4h-bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgj4h-bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:split-cells-outline" /></template>
