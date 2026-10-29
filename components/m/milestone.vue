<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg-0z5wjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg-0z5wjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:milestone" /></template>
