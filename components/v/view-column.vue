<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpfv3y81q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpfv3y81q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:view-column" /></template>
