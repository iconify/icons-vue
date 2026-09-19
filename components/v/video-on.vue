<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keijgb3kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keijgb3kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:video-on" /></template>
