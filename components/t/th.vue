<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufay8wlzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufay8wlzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:th" /></template>
