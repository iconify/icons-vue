<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp0kc7r6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp0kc7r6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:play-1" /></template>
