<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuk2eibqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuk2eibqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:note" /></template>
