<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uft75ab9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uft75ab9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-fill" /></template>
