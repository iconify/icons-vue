<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrus7ebnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrus7ebnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pencil" /></template>
